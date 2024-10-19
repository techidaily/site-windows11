---
title: Is WSL Functional Post-Windows 11 Install? Solutions Explored
date: 2024-10-14T01:28:23.196Z
updated: 2024-10-18T19:51:27.421Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Is WSL Functional Post-Windows 11 Install? Solutions Explored
excerpt: This Article Describes Is WSL Functional Post-Windows 11 Install? Solutions Explored
keywords: Windows 11 WSL Status,Post-Install WSL Usability,WSL Compatibility Windows 11,Solve WSL Issues Win11,WSL Functionality Update,WSL Post-Win11 Fixes,Explore WSL Post-Windows 11
thumbnail: https://thmb.techidaily.com/5b6554e76aaa2a052eebb5ed360ccf43529d16f47d56cedf742a90d738a59cc9.jpg
---

## Is WSL Functional Post-Windows 11 Install? Solutions Explored

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123730/7443" target="_top" id="2123730">
  <img src="//a.impactradius-go.com/display-ad/7443-2123730" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123730/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Enable Hyper-V and Virtual Machine Platform

 If you want to use a subsystem such as WSL in Windows, you'll also need to enable the virtualization tools. These include Hyper-V and the Virtual Machine Platform.

![Error message in the command line interface](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-feature-missing.jpg)

 If a command line interface opens, telling you a required feature is not installed, when you try to run your Linux distribution, this is likely what it refers to.

1. Search for**Turn Windows features on or off** and click the search result.
2. In Windows Features, scroll down to find**Virtual Machine Platform** and**Windows Hypervisor Platform** .
3. Check the boxes next to each of these features and then click**Ok** .
4. You will need to restart your computer to complete the installation of these tools.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118326/7443" target="_top" id="2118326">
  <img src="//a.impactradius-go.com/display-ad/7443-2118326" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118326/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Repair the Linux Distribution App

 Your Linux distribution app, such as Ubuntu, Kali, or Debian, could be corrupted or require updating. This can cause WSL to appear to be broken. Repairing Windows apps is very easy.

1. Open**Settings > Apps > App & Features** .
2. Scroll down to the list of your apps to find your Linux distro app.
3. Click the**three dots** to the right of the app name, and select**Advanced options** .  
![Advanced app options in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl.jpg)
4. Click the**Repair** button and follow the on-screen instructions if repairs are necessary.  
![repairing an app in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl-app.jpg)

 Check if WSL is working. If not, try uninstalling and reinstalling the Linux distribution app.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136612/26400" target="_top" id="2136612">
  <img src="//a.impactradius-go.com/display-ad/26400-2136612" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136612/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Force WSL to Open Using the Microsoft Store

 If WSL is enabled but still refuses to open, you can try forcing launch through the Microsoft Store app. This can sometimes fix temporary glitches when opening WSL directly doesn't work.

1. Open the Microsoft Store app and search for**WSL** .
2. On the store page for WSL, you should see an**Open** button. If the button says**Update** , click it to update the app.  
![opening the WSL app in the Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/force-open-store.jpg)
3. Click the**Open** button, and the default Linux distro app should launch.
4. If a command line interface window opens instead, it will probably tell you a required feature is missing. See**Enable Hyper-V and Virtual Machine Platform** above.

 If forcing WSL to open doesn't work, try the same with the Linux distro app you are using. Open the Store, search for your distro, and click the**Open** button.

## 5\. Uninstall Recent Updates to Fix WSL

 If WSL stopped working after installing an update, the update could be the cause. You can uninstall the most recent update to see if that fixes the problem.

[Uninstalling Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) isn't a complicated process, even if you have never done it before.

 If, after uninstalling the update, WSL still does not work, it is a good idea to reinstall it. Updates can often include security and performance tweaks, so it is generally recommended to keep Windows updated.

## 6\. Check That Malware Isn't Blocking WSL

 The final thing to try to get WSL working is scanning for malware. The potential for malware to prevent Windows Subsystem for Linux from working is low but not unheard of.

 Run a[full scan in Microsoft Defender](https://www.makeuseof.com/easy-ways-boost-security-microsoft-defender-and-windows-10/) or whichever third-party antivirus software you use. Quarantine or remove any malware your antivirus scan finds. Then restart your computer and try using WSL to see if that was the issue.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135402/19272" target="_top" id="2135402">
  <img src="//a.impactradius-go.com/display-ad/19272-2135402" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135402/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://fox-cloud.techidaily.com/new-diving-deep-into-whatsapps-vocal-messaging-experience/"><u>[New] Diving Deep Into WhatsApp's Vocal Messaging Experience</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-mobile-markup-mastery-iosandroid-leaders/"><u>[Updated] 2024 Approved Mobile Markup Mastery IOS/Android Leaders</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-elevating-your-gameplay-on-youtube-with-these-essential-tags/"><u>[Updated] Elevating Your Gameplay on YouTube with These Essential Tags</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-expert-advice-enhancing-your-screen-capture-game-with-mobizen-tools/"><u>[Updated] In 2024, Expert Advice Enhancing Your Screen Capture Game with Mobizen Tools</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-rookie-riches-economical-channels-for-monetization/"><u>[Updated] In 2024, Rookie Riches Economical Channels for Monetization</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/easy-steps-for-precise-clip-slicing-and-reshaping-in-adobe-after-effects-beginners-guide-to-efficient-video-editing/"><u>Easy Steps for Precise Clip Slicing and Reshaping in Adobe After Effects - Beginner's Guide to Efficient Video Editing</u></a></li>
<li><a href="https://youtube-web.techidaily.com/iently-engaging-with-numerous-youtube-lectures/"><u>Efficiently Engaging with Numerous YouTube Lectures</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-for-windows-0x80780119-error-in-image/"><u>Fix for Windows' 0X80780119 Error in Image</u></a></li>
<li><a href="https://windows11.techidaily.com/fortify-your-pc-with-these-7-leading-gratis-password-apps/"><u>Fortify Your PC with These 7 Leading, Gratis Password Apps</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/funimate-pro-unboxed-your-essential-apk-guide-for-2024/"><u>Funimate Pro Unboxed Your Essential APK Guide for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-how-to-generate-a-copernic-software-offline-license/"><u>Guide: How to Generate a Copernic Software Offline License</u></a></li>
<li><a href="https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-vivo-v30-drfone-by-drfone-virtual-android/"><u>Is pgsharp legal when you are playing pokemon On Vivo V30? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-quick-finds-in-illustrator-a-complete-guide-using-copernic/"><u>Mastering Quick Finds in Illustrator: A Complete Guide Using Copernic</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-flawless-file-handling-discover-copernics-software-secrets-for-maximum-efficiency/"><u>Navigating Flawless File Handling: Discover Copernic's Software Secrets for Maximum Efficiency</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/on-the-spot-screen-savers-facebook-edition/"><u>On-the-Spot Screen Savers - Facebook Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionizing-business-data-retrieval-with-advanced-copernic-search-tech-explained/"><u>Revolutionizing Business Data Retrieval with Advanced Copernic Search Tech Explained</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-triple-column-tiles-on-windows-11-a-quick-guide/"><u>Setting Up Triple Column Tiles on Windows 11 – A Quick Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-your-media-experience-with-wmp/"><u>Streamlining Your Media Experience with WMP</u></a></li>
<li><a href="https://windows11.techidaily.com/top-strategies-for-resolving-windows-11-onedrive-disconnects/"><u>Top Strategies for Resolving Windows 11 OneDrive Disconnects</u></a></li>
</ul></div>

