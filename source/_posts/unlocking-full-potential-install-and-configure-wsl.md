---
title: "Unlocking Full Potential: Install and Configure WSL"
date: 2024-10-04T22:50:58.812Z
updated: 2024-10-06T16:38:14.553Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlocking Full Potential: Install and Configure WSL"
excerpt: "This Article Describes Unlocking Full Potential: Install and Configure WSL"
keywords: WSL Setup Basics,Windows Subsystem Enablement,WSL Configuration Guide,Unleash WSL Capabilities,Linux on Windows Installation,Configure WSL Successfully,WSL Performance Tuning
thumbnail: https://thmb.techidaily.com/dc0976bf992fc8f3795e090c13f66cb1c6f1455915fe3cbbbf65ceba836d3f9e.jpg
---

## Unlocking Full Potential: Install and Configure WSL

### Key Takeaways

* You must enable Windows Subsystem for Linux (WSL) before you can install a Linux distribution on a Windows PC.
* Not all Windows 10 versions are compatible with WSL, but all Windows 11 versions are.
* The updated WSL2 is more convenient and gives better performance, but you can switch to WSL1 to suit specific needs.

 If you want to run a Linux terminal on Windows, your best bet would be to enable Windows Subsystem for Linux (WSL), a gateway opener that allows you to install a Linux bash shell on a Windows OS. Once you’ve enabled WSL, you can install a Linux distro.

## Requirements for Running WSL on Windows 10

 Before you enable Windows Subsystem for Linux, you should know of the minimum requirements needed to run WSL.

[According to Microsoft](https://learn.microsoft.com/en-us/windows/wsl/install), you should be running Windows 10 (64-bit) version 2004 or higher with Build 19041 or higher.

 All Windows 11 versions can run WSL.

 If you’re not sure of your Windows 10 flavor, it’s easy to [check which version of Windows 10 you have installed](https://www.makeuseof.com/tag/how-to-check-windows-10-version-build/).

 Some older versions of Windows 10 can also work, but you’ll have to manually install WSL.

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098701/14409" target="_top" id="2098701">
  <img src="//a.impactradius-go.com/display-ad/14409-2098701" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098701/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Enable Windows Subsystem for Linux

 In order to install the Linux bash shell on Windows 10, you first have to enable Windows Subsystem for Linux.

 You’ll know if WSL isn't enabled because you’ll run into the error: “The Windows Subsystem for Linux optional component is not enabled. Please enable it and try again.”

 Here’s how to enable WSL in Windows 10:

 You first need to get into Windows **Programs and Features**.

1. Open Windows 10 **Settings** and select **Apps**.
2. On the right side of the window, under **Related settings**, click on **Programs and Features**.

![Programs and Features option under the Related settings section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/program-and-features-option-in-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/2139558/4704" target="_top" id="2139558">
  <img src="//a.impactradius-go.com/display-ad/4704-2139558" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/2139558/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you’re in, click on **Turn Windows features on or off** on the left panel. Then scroll down and check the corresponding box to enable Windows Subsystem for Linux.

![Windows Subsystem for Linux option in Windows Features page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/enable-wsl-windows-10.jpg)

 Click **OK** to save your changes and hit **Restart now** to finish the process.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130531/26400" target="_top" id="2130531">
  <img src="//a.impactradius-go.com/display-ad/26400-2130531" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130531/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Installing WSL on a Windows Machine

 With WSL enabled on your Windows device, you can [install Windows Subsystem for Linux](https://www.makeuseof.com/tag/linux-bash-shell-on-windows-10/). After that, you can install any supported Linux distro right inside your Windows PC. Choosing a [small, lightweight Linux distro](https://www.makeuseof.com/tag/linux-distro-space/) might be helpful.

 You can also [install a Linux desktop in Windows](https://www.makeuseof.com/tag/linux-desktop-windows-subsystem/) that gives you a graphical UI to work with.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915825/19272" target="_top" id="1915825">
  <img src="//a.impactradius-go.com/display-ad/19272-1915825" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915825/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## WSL1 or WSL2: Which Is Better For You?

 WSL2 is an upgraded version of Windows Subsystem for Linux and is now the default when installing a Linux distribution in Windows. It works with Windows 11 or Windows 10, Version 1903, Build 18362 or higher.

 There are a few differences between the two versions of WSL; chiefly, WSL2 offers better performance in addition to support for full system call compatibility and IPv6 support. Also, WSL2 uses a full Linux kernel inside a managed virtual machine (VM), so you don’t have to set up and manage a VM to run a Linux distro.

### Reasons to Switch to WSL1

 While the latest version of WSL offers better performance and a wider range of support, there are reasons you may want to use the older version. This is because WSL1 runs with older versions of VMware and VirtualBox—and WSL2 does not, although it is compatible with the latest versions of VirtualBox and VMware, which both support Hyper-V.

 The main reason to use WSL1 instead of WSL2 is that it offers better performance across OS file systems—a hurdle that can be overcome by creating your project files in the Linux file system.

 With WSL enabled and a Linux distro installed, you’ll be on your way to executing commands.

 If you want to run a Linux terminal on Windows, your best bet would be to enable Windows Subsystem for Linux (WSL), a gateway opener that allows you to install a Linux bash shell on a Windows OS. Once you’ve enabled WSL, you can install a Linux distro.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-capture.techidaily.com/new-premium-android-screenshot-and-video-tools-ranked-five-for-2024/"><u>[New] Premium Android Screenshot & Video Tools - Ranked Five for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-behind-the-mascara-youtubes-top-makeup-artists-unveiled-for-2024/"><u>[Updated] Behind the Mascara YouTube's Top Makeup Artists Unveiled for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-optimize-your-online-presence-youtube-to-dailymotion-video-migration/"><u>[Updated] Optimize Your Online Presence YouTube to Dailymotion Video Migration</u></a></li>
<li><a href="https://windows11.techidaily.com/discover-restful-nights-with-the-ihome-zenergy-bedside-sleep-enhancer-comprehensive-review/"><u>Discover Restful Nights with the IHome Zenergy Bedside Sleep Enhancer – Comprehensive Review</u></a></li>
<li><a href="https://vp-tips.techidaily.com/first-timers-roadmap-earning-money-from-periscope-chats-for-2024/"><u>First-Timer's Roadmap Earning Money From Periscope Chats for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/gift-ideas-for-a-christmasy-windows-11-experience/"><u>Gift Ideas for a Christmasy Windows 11 Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-revealing-your-pcs-background-image-storage/"><u>Guide to Revealing Your PC’s Background Image Storage</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-users-through-windows-error-0x0000004e-woes/"><u>Guiding Users Through Windows' Error 0X0000004E Woes</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/how-to-create-engaging-screencasts-a-practical-guide/"><u>How to Create Engaging Screencasts A Practical Guide</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-solve-detected-hardware-not-recognized-message-in-idt-software-packages/"><u>How To Solve 'Detected Hardware Not Recognized' Message in IDT Software Packages</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-tackle-photo-errors-in-windows-devices/"><u>How to Tackle Photo Errors in Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/make-the-most-of-older-os-a-guide-beyond-windows-11/"><u>Make the Most of Older OS: A Guide Beyond Windows 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/polishing-zoom-picture-quality-simple-solutions/"><u>Polishing Zoom Picture Quality Simple Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/smooth-transition-with-easy-steps-surface-pcs-version-enhancement-guide/"><u>Smooth Transition with Easy Steps: Surface PCs' Version Enhancement Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-revive-non-launching-obs-on-windows/"><u>Steps to Revive Non-Launching OBS on Windows</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-ultimate-guide-to-best-free-split-screen-recording-tools-for-videos-onlineoffline/"><u>The Ultimate Guide to Best FREE Split Screen Recording Tools for Videos (Online/Offline)</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-error-with-steam-apps-dll/"><u>Troubleshooting Error with Steam App's Dll</u></a></li>
</ul></div>

