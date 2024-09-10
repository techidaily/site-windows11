---
title: "Post-Upgrade: Realignment of the Windows and WSL System"
date: 2024-09-09T12:03:42.894Z
updated: 2024-09-10T12:03:42.894Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Post-Upgrade: Realignment of the Windows and WSL System"
excerpt: "This Article Describes Post-Upgrade: Realignment of the Windows and WSL System"
keywords: WinWSL Upgrade Impact,Windows WSL Realign,Post-Upgrade WSL Guide,WSL Realignment Steps,Enhancing WinWSL System,WSL Performance After Upgrade,Optimizing Windows for WSL
thumbnail: https://thmb.techidaily.com/295eb1a512b03cd4604053efc700e515a23fe08d7898031d0786b31b79d36b64.jpg
---

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137225/26400" target="_top" id="2137225">
  <img src="//a.impactradius-go.com/display-ad/26400-2137225" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137225/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Post-Upgrade: Realignment of the Windows and WSL System

 There are several potential reasons why Windows Subsystem for Linux (WSL) stopped working after your PC was upgraded to Windows 11\. Thankfully, the breakdown is unlikely to be terminal, although you might have to try a few different fixes to get it working once again.

 **MUO VIDEO OF THE DAY**

 **SCROLL TO CONTINUE WITH CONTENT**

 Here are several ways to get the Windows Subsystem for Linux working again after upgrading to Windows 11.

## 1\. Check That WSL Is Enabled

 It isn't unusual that upgrading to a newer version of the OS will break some apps and features. So although it might sound obvious, checking WSL hasn't simply been disabled during the upgrade process should be your first step. Here's how to check:

![checking if WSL is enabled in Windows Features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-enabled.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130886/7443" target="_top" id="2130886">
  <img src="//a.impactradius-go.com/display-ad/7443-2130886" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130886/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
1. In Windows Search, type**Turn Windows features on or off** and click the search result that should appear at the top.
2. In the Windows System dialog, scroll down until you see**Windows Subsystem for Linux** .
3. If the checkbox for the feature is not selected, do so now. Then click**Ok** .
4. You might also need to restart your computer before checking to see if that fixed the problem.

 Hopefully, WSL is now working, and you can begin using the tool. If not, read on for some other possible solutions.

 Learn more about the[things you can do with WSL and Linux](https://www.makeuseof.com/pros-cons-windows-subsystem-for-linux/) on your Windows computer.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123471/16836" target="_top" id="2123471">
  <img src="//a.impactradius-go.com/display-ad/16836-2123471" border="0" alt="https://techidaily.com" width="234" height="60"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123471/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Enable Hyper-V and Virtual Machine Platform

 If you want to use a subsystem such as WSL in Windows, you'll also need to enable the virtualization tools. These include Hyper-V and the Virtual Machine Platform.

![Error message in the command line interface](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-feature-missing.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115909/19272" target="_top" id="2115909">
  <img src="//a.impactradius-go.com/display-ad/19272-2115909" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115909/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115947/19272" target="_top" id="2115947">
  <img src="//a.impactradius-go.com/display-ad/19272-2115947" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115947/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![repairing an app in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl-app.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134496/18498" target="_top" id="2134496">
  <img src="//a.impactradius-go.com/display-ad/18498-2134496" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134496/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-a-step-by-step-guide-to-utilizing-bandicams-capture-feature/"><u>[New] 2024 Approved A Step-by-Step Guide to Utilizing Bandicam's Capture Feature</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-innovative-strategies-to-enhance-video-craftsmanship-on-windows-10/"><u>[New] In 2024, Innovative Strategies to Enhance Video Craftsmanship on Windows 10</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-harnessing-the-power-of-software-for-seamless-vimeo-video-downloads/"><u>[Updated] 2024 Approved Harnessing the Power of Software for Seamless Vimeo Video Downloads</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-the-ultimate-5-online-av-creation-leaders/"><u>[Updated] In 2024, The Ultimate 5 Online AV Creation Leaders</u></a></li>
<li><a href="https://location-fake.techidaily.com/10-best-fake-gps-location-spoofers-for-vivo-t2-pro-5g-drfone-by-drfone-virtual-android/"><u>10 Best Fake GPS Location Spoofers for Vivo T2 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-mastering-photo-blur-the-most-valuable-pixelation-software/"><u>2024 Approved Mastering Photo Blur The Most Valuable Pixelation Software</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-top-5-web-video-recorders/"><u>2024 Approved Top 5 Web Video Recorders</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-best-route-generator-apps-you-should-try-on-motorola-moto-g14-drfone-by-drfone-virtual-android/"><u>5 Best Route Generator Apps You Should Try On Motorola Moto G14 | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/easily-unlock-your-motorola-moto-g23-device-sim-by-drfone-android/"><u>Easily Unlock Your Motorola Moto G23 Device SIM</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-unresponsive-windows-11-search-engine/"><u>Fixing Unresponsive Windows 11 Search Engine</u></a></li>
<li><a href="https://windows11.techidaily.com/gain-mastery-over-files-in-windows-11-quick-transition-tricks/"><u>Gain Mastery Over Files in Windows 11: Quick Transition Tricks</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-unlock-hidden-bluetooth-clients-in-device-hub/"><u>Guide: Unlock Hidden Bluetooth Clients in Device Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/highlighting-the-superiority-win11-over-macos-details/"><u>Highlighting The Superiority: Win11 over MacOS Details</u></a></li>
<li><a href="https://windows11.techidaily.com/how-does-microsoft-make-money-from-windows-11/"><u>How Does Microsoft Make Money From Windows 11?</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-active-directory-domain-services-printer-error-in-windows-10-and-11/"><u>How to Fix the “Active Directory Domain Services” Printer Error in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-revive-and-restart-stuck-spotify-on-w10w11-pcs/"><u>How to Revive and Restart Stuck Spotify on W10/W11 PCs</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-bridging-worlds-a-deep-dive-into-vr-developments/"><u>In 2024, Bridging Worlds A Deep Dive Into VR Developments</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-images-on-the-lock-screen-on-or-off-windows-style/"><u>Mastery of Images on the Lock Screen: On or Off, Windows Style</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-graphics-drivers-a-windows-10-and-11-fixation/"><u>Navigating Graphics Drivers: A Windows 10 & 11 Fixation</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-steam-audio-latency-troubleshooting/"><u>Navigating Windows Steam Audio Latency Troubleshooting</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-cameras-unsaved-photos-hurdle/"><u>Overcoming Windows Camera's Unsaved Photos Hurdle</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-pc-performance-set-active-hours-prevent-sudden-updates-on-windows-11/"><u>Perfecting PC Performance: Set Active Hours, Prevent Sudden Updates on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/pure-functionality-cleaning-and-organizing-your-w11-workspace/"><u>Pure Functionality: Cleaning and Organizing Your W11 Workspace</u></a></li>
<li><a href="https://windows11.techidaily.com/re-enabling-print-service-after-error-displayed-on-pc/"><u>Re-Enabling Print Service After Error Displayed on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-portaudio-faults-in-audacity-for-windows-1111-os/"><u>Resolving PortAudio Faults in Audacity for Windows 11/11 OS</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-workflow-excellent-screen-savers-with-clock-features/"><u>Seamless Workflow: Excellent Screen Savers with Clock Features</u></a></li>
<li><a href="https://windows11.techidaily.com/skillful-art-of-masking-the-search-on-11-taskbar/"><u>Skillful Art of Masking the Search on 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/stealthy-start-concealing-win11s-power-button-in-start-menu/"><u>Stealthy Start: Concealing Win11's Power Button in Start Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-securely-storing-credentials-in-windows-files/"><u>Step-by-Step: Securely Storing Credentials in Windows Files</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-rectifying-audacitys-audio-access-issue/"><u>Steps for Rectifying Audacity’s Audio Access Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-your-approach-to-fixing-installer-error-in-win11/"><u>Streamlining Your Approach to Fixing Installer Error in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-error-at-interrupt-during-debugging-windows/"><u>Tackling Error at Interrupt During Debugging Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-icon-cache-revival-in-win10win11/"><u>Techniques for Icon Cache Revival in Win10/Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-core-skills-for-conquering-classic-diablos-world/"><u>The Core Skills for Conquering Classic Diablo's World</u></a></li>
<li><a href="https://windows11.techidaily.com/the-peculiar-path-to-a-plain-start-menu/"><u>The Peculiar Path to a Plain Start Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-roblox-windows-errors/"><u>Troubleshooting Roblox Windows Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-the-power-of-windows-11-taskbar-for-maximum-output/"><u>Unleash the Power of Windows 11 Taskbar for Maximum Output</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-1011-old-login-logon-error/"><u>Unlocking Windows 10/11: Old Login Logon Error</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11-access-a-step-by-step-guide/"><u>Unlocking Windows 11 Access: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-copilot-microsofts-ai-code-companion/"><u>Unveiling Copilot: Microsoft's AI Code Companion</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-methods-for-vanished-folder-recovery-on-windows/"><u>Unveiling Methods for Vanished Folder Recovery on Windows</u></a></li>
</ul></div>
