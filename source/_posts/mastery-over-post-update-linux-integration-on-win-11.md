---
title: Mastery Over Post-Update Linux Integration on Win 11
date: 2024-10-17T21:32:18.709Z
updated: 2024-10-19T01:44:19.954Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastery Over Post-Update Linux Integration on Win 11
excerpt: This Article Describes Mastery Over Post-Update Linux Integration on Win 11
keywords: Linux Win Update Mastery,Post-Update Linux Win,Win11 Linux Integration,Linux Update Seamless,Win11 Linux Harmony,Linux Upgrade Windows,Optimal Linux Update
thumbnail: https://thmb.techidaily.com/a7021ad624ff445cc29baa46a54eaf2cd9c23802b899b1042a541c20e9321a2f.jpg
---

## Mastery Over Post-Update Linux Integration on Win 11

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136615/26400" target="_top" id="2136615">
  <img src="//a.impactradius-go.com/display-ad/26400-2136615" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136615/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047351/19272" target="_top" id="2047351">
  <img src="//a.impactradius-go.com/display-ad/19272-2047351" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047351/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. If a command line interface window opens instead, it will probably tell you a required feature is missing. See**Enable Hyper-V and Virtual Machine Platform** above.

 If forcing WSL to open doesn't work, try the same with the Linux distro app you are using. Open the Store, search for your distro, and click the**Open** button.

## 5\. Uninstall Recent Updates to Fix WSL

 If WSL stopped working after installing an update, the update could be the cause. You can uninstall the most recent update to see if that fixes the problem.

[Uninstalling Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) isn't a complicated process, even if you have never done it before.

 If, after uninstalling the update, WSL still does not work, it is a good idea to reinstall it. Updates can often include security and performance tweaks, so it is generally recommended to keep Windows updated.

<!-- affiliate ads begin -->
<span id="1630055">
					<video width="192" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1630055.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18460-1630055">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1630055.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:120px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fcaperobbin.sjv.io%2Fc%2F5597632%2F1630055%2F18460'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1630055/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Check That Malware Isn't Blocking WSL

 The final thing to try to get WSL working is scanning for malware. The potential for malware to prevent Windows Subsystem for Linux from working is low but not unheard of.

 Run a[full scan in Microsoft Defender](https://www.makeuseof.com/easy-ways-boost-security-microsoft-defender-and-windows-10/) or whichever third-party antivirus software you use. Quarantine or remove any malware your antivirus scan finds. Then restart your computer and try using WSL to see if that was the issue.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130890/7443" target="_top" id="2130890">
  <img src="//a.impactradius-go.com/display-ad/7443-2130890" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130890/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-docs.techidaily.com/arnessing-youtube-statistics-to-increase-subscribers/"><u>[New] Harnessing YouTube Statistics to Increase Subscribers</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-simplified-systems-for-saving-screen-calls/"><u>[Updated] Simplified Systems for Saving Screen Calls</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-smooth-transition-from-skype-to-zoom-for-better-collaboration/"><u>[Updated] Smooth Transition From Skype to Zoom for Better Collaboration</u></a></li>
<li><a href="https://howto.techidaily.com/calls-on-itel-s23-go-straight-to-voicemail-12-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Calls on Itel S23 Go Straight to Voicemail? 12 Fixes | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-the-ring-with-video-recording-who-will-triumph-obs-or-bandicam-for-2024/"><u>In the Ring with Video Recording Who Will Triumph, OBS or Bandicam for 2024</u></a></li>
<li><a href="https://buynow-help.techidaily.com/in-depth-evaluation-of-microsoft-surface-laptop-4s-exceptional-quality/"><u>In-Depth Evaluation of Microsoft Surface Laptop 4'S Exceptional Quality</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-needs-old-pass-troubleshooting-tips/"><u>Resolving Windows Needs Old Pass: Troubleshooting Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/reversing-unable-to-open-share-issue-in-windows/"><u>Reversing Unable to Open Share Issue in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/revising-windows-1011-login-limit-settings-post-failed-sign-ins/"><u>Revising Windows 10/11 Login Limit Settings Post-Failed Sign-Ins</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-art-of-hue-adjustment-in-post-production/"><u>The Art of Hue Adjustment in Post-Production</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-image-rotation-on-your-windows-11-pc/"><u>The Art of Image Rotation on Your Windows 11 PC</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-ultimate-fix-addressing-and-correcting-kernel32dll-complications-in-windows/"><u>The Ultimate Fix: Addressing and Correcting Kernel32.dll Complications in Windows</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/unveiling-the-high-res-sky-scenes-with-mi-drone-for-2024/"><u>Unveiling the High-Res Sky Scenes with Mi Drone for 2024</u></a></li>
</ul></div>

