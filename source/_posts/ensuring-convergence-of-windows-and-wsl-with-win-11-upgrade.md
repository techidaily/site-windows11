---
title: Ensuring Convergence of Windows & WSL with Win 11 Upgrade
date: 2024-07-11T21:30:42.358Z
updated: 2024-07-12T21:30:42.358Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Ensuring Convergence of Windows & WSL with Win 11 Upgrade
excerpt: This Article Describes Ensuring Convergence of Windows & WSL with Win 11 Upgrade
keywords: Windows-WSL Integration,Win 11 Upgrade Impact,Converging Operating Systems,Enhancing WSL Compatibility,Win11 & Linux Alignment,OS Update Strategies,Streamlining Windows-Linux
thumbnail: https://thmb.techidaily.com/8cc7746fe0672e4725ddd5d1492632738fafd136f8e04394f483f1432a572415.png
---

## Ensuring Convergence of Windows & WSL with Win 11 Upgrade

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

 Learn more about the [things you can do with WSL and Linux](https://www.makeuseof.com/pros-cons-windows-subsystem-for-linux/) on your Windows computer.

## 2\. Enable Hyper-V and Virtual Machine Platform

 If you want to use a subsystem such as WSL in Windows, you'll also need to enable the virtualization tools. These include Hyper-V and the Virtual Machine Platform.

![Error message in the command line interface](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-feature-missing.jpg)

 If a command line interface opens, telling you a required feature is not installed, when you try to run your Linux distribution, this is likely what it refers to.

1. Search for**Turn Windows features on or off** and click the search result.
2. In Windows Features, scroll down to find**Virtual Machine Platform** and**Windows Hypervisor Platform** .
3. Check the boxes next to each of these features and then click**Ok** .
4. You will need to restart your computer to complete the installation of these tools.

## 3\. Repair the Linux Distribution App

 Your Linux distribution app, such as Ubuntu, Kali, or Debian, could be corrupted or require updating. This can cause WSL to appear to be broken. Repairing Windows apps is very easy.

1. Open**Settings > Apps > App & Features** .
2. Scroll down to the list of your apps to find your Linux distro app.
3. Click the**three dots** to the right of the app name, and select**Advanced options** .  
![Advanced app options in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl.jpg)
4. Click the**Repair** button and follow the on-screen instructions if repairs are necessary.  
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

## 5\. Uninstall Recent Updates to Fix WSL

 If WSL stopped working after installing an update, the update could be the cause. You can uninstall the most recent update to see if that fixes the problem.

[Uninstalling Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) isn't a complicated process, even if you have never done it before.

 If, after uninstalling the update, WSL still does not work, it is a good idea to reinstall it. Updates can often include security and performance tweaks, so it is generally recommended to keep Windows updated.

## 6\. Check That Malware Isn't Blocking WSL

 The final thing to try to get WSL working is scanning for malware. The potential for malware to prevent Windows Subsystem for Linux from working is low but not unheard of.

 Run a [full scan in Microsoft Defender](https://www.makeuseof.com/easy-ways-boost-security-microsoft-defender-and-windows-10/) or whichever third-party antivirus software you use. Quarantine or remove any malware your antivirus scan finds. Then restart your computer and try using WSL to see if that was the issue.

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
<li><a href="https://windows11.techidaily.com/unsticking-wows-initialization-on-pcs/"><u>Unsticking WoW's Initialization on PCs</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-honor-magic-6-lite-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos From Honor Magic 6 Lite to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-error-0x80072f8f-0x20000-in-windows/"><u>Troubleshooting Error 0X80072f8f - 0X20000 in Windows</u></a></li>
<li><a href="https://howto.techidaily.com/8-quick-fixes-unfortunately-snapchat-has-stopped-on-infinix-note-30i-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Quick Fixes Unfortunately, Snapchat has Stopped on Infinix Note 30i | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-drone-photographers-stabilization-companion/"><u>[Updated] The Drone Photographer's Stabilization Companion</u></a></li>
<li><a href="https://howto.techidaily.com/super-easy-ways-to-deal-with-vivo-v30-unresponsive-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Super Easy Ways To Deal with Vivo V30 Unresponsive Screen | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-leave-a-life360-group-on-nokia-c12-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How To Leave a Life360 Group On Nokia C12 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/quick-guide-bypassing-edgenuity-courses-seamlessly/"><u>Quick Guide  Bypassing Edgenuity Courses Seamlessly</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-your-experience-using-w11s-auto-hdr/"><u>Tailoring Your Experience: Using W11's Auto HDR</u></a></li>
<li><a href="https://windows11.techidaily.com/responding-to-click-failures-in-windows-11-environment/"><u>Responding to Click Failures in Windows 11 Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/tricks-to-launch-websites-after-installation/"><u>Tricks to Launch Websites After Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-the-process-anydesk-fixes-for-windows-users/"><u>Simplifying the Process: AnyDesk Fixes for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-making-the-cursor-more-noticeable-in-windows/"><u>Step-by-Step: Making the Cursor More Noticeable in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-machine-wattage-determining-computational-power-use/"><u>Windows Machine Wattage: Determining Computational Power Use</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/the-complete-guide-to-infinix-smart-8-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>The Complete Guide to Infinix Smart 8 FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://windows11.techidaily.com/sharpening-performance-with-optimized-news-and-video-consumption/"><u>Sharpening Performance with Optimized News & Video Consumption</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-excellence-guild-crafting-photos-plus-sounds-visuals/"><u>[New] Excellence Guild  Crafting Photos + Sounds, Visuals</u></a></li>
<li><a href="https://windows11.techidaily.com/why-microsoft-family-safety-matters-for-parents/"><u>Why Microsoft Family Safety Matters for Parents</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshoot-and-fix-windows-autoshrink-issue/"><u>Troubleshoot & Fix Windows' Autoshrink Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-terminal-for-quake-in-windows/"><u>Configuring Terminal for Quake in Windows</u></a></li>
<li><a href="https://discord-videos.techidaily.com/seamless-blend-linking-spotify-and-discord-directly-for-2024/"><u>Seamless Blend  Linking Spotify & Discord Directly for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/the-ultimate-list-for-fbs-most-popular-song-videos/"><u>The Ultimate List for FB's Most Popular Song Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-error-code-0x80071a90-in-windows/"><u>Unraveling Error Code 0X80071A90 in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/6-quick-ways-to-fix-the-powerpoint-cant-save-file-error-in-windows-11/"><u>6 Quick Ways to Fix the PowerPoint Can't Save File Error in Windows 11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-mastering-the-integration-of-b-roll-footage/"><u>[New] Mastering the Integration of B-Roll Footage</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-windows-11-in-place-update-mastery/"><u>Step-by-Step Windows 11, In-Place Update Mastery</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-edit-and-send-fake-location-on-telegram-for-your-nubia-z50s-pro-in-3-ways-drfone-by-drfone-virtual-android/"><u>In 2024, Edit and Send Fake Location on Telegram For your Nubia Z50S Pro in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-facts-you-need-to-know-about-screen-mirroring-asus-rog-phone-7-drfone-by-drfone-android/"><u>In 2024, 3 Facts You Need to Know about Screen Mirroring Asus ROG Phone 7 | Dr.fone</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-iphone-hdr-photography-for-enthusiasts/"><u>[New] In 2024, IPhone HDR Photography for Enthusiasts</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-what-does-jailbreaking-apple-iphone-13-pro-max-i-do-get-answers-here-by-drfone-ios/"><u>In 2024, What Does Jailbreaking Apple iPhone 13 Pro Max i Do? Get Answers here</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/4-methods-to-record-gameplay-on-xbox-one/"><u>4 Methods to Record Gameplay on Xbox One</u></a></li>
<li><a href="https://windows11.techidaily.com/simple-steps-for-screen-position-changes/"><u>Simple Steps for Screen Position Changes</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-to-successful-os-transition-in-virtual-worlds/"><u>Unveiling the Secrets to Successful OS Transition in Virtual Worlds</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-stop-motion-mastery-on-instagram-from-basics-to-pro/"><u>Updated In 2024, Stop Motion Mastery on Instagram From Basics to Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/top-secure-password-vaults-elevating-windows-11-standards/"><u>Top Secure Password Vaults Elevating Windows 11 Standards</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-a-unique-win11-screenscape-display/"><u>Setting Up a Unique Win11 Screenscape Display</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-financial-gains-with-w11-pro-key-deals/"><u>Unlock Financial Gains with W11 Pro Key Deals</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-at-learning-7-efficient-techniques-for-windows/"><u>Winning at Learning: 7 Efficient Techniques for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-unblock-windows-nvidia-setup-window/"><u>Strategies to Unblock Windows Nvidia Setup Window</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-tips-for-efficient-toolbar-usage-in-microsoft-win11-pcm/"><u>Advanced Tips for Efficient Toolbar Usage in Microsoft Win11 PCM</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-unpredictable-power-estimator-display-on-windows-11/"><u>Correcting Unpredictable Power Estimator Display on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-search-tweaks-enhancing-your-experience/"><u>Windows 11'S Search Tweaks: Enhancing Your Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-access-permissions-biometrics-on-w11-domains/"><u>Streamlining Access Permissions: Biometrics on W11, Domains</u></a></li>
</ul></div>
