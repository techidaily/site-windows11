---
title: "Simplified Integration: How to Set Up Linux in Your Win10 Box"
date: 2024-11-01T22:16:38.480Z
updated: 2024-11-05T09:39:56.530Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Simplified Integration: How to Set Up Linux in Your Win10 Box"
excerpt: "This Article Describes Simplified Integration: How to Set Up Linux in Your Win10 Box"
keywords: Windows/Linux Combo,Simple Linux Install,Win10 Linux Compatibility,Easy Linux on Windows,Linux Integration Guide,Linux Setup in Win10,Cross-Platform Linux Use
thumbnail: https://thmb.techidaily.com/e4dab8212b61415ab670db2724890039dc218886423e579644f1092e23638fe5.jpg
---

## Simplified Integration: How to Set Up Linux in Your Win10 Box

### Key Takeaways

* You must enable Windows Subsystem for Linux (WSL) before you can install a Linux distribution on a Windows PC.
* Not all Windows 10 versions are compatible with WSL, but all Windows 11 versions are.
* The updated WSL2 is more convenient and gives better performance, but you can switch to WSL1 to suit specific needs.

 If you want to run a Linux terminal on Windows, your best bet would be to enable Windows Subsystem for Linux (WSL), a gateway opener that allows you to install a Linux bash shell on a Windows OS. Once you’ve enabled WSL, you can install a Linux distro.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016165/19272" target="_top" id="2016165">
  <img src="//a.impactradius-go.com/display-ad/19272-2016165" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016165/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Requirements for Running WSL on Windows 10

 Before you enable Windows Subsystem for Linux, you should know of the minimum requirements needed to run WSL.

[According to Microsoft](https://learn.microsoft.com/en-us/windows/wsl/install), you should be running Windows 10 (64-bit) version 2004 or higher with Build 19041 or higher.

 All Windows 11 versions can run WSL.

 If you’re not sure of your Windows 10 flavor, it’s easy to [check which version of Windows 10 you have installed](https://www.makeuseof.com/tag/how-to-check-windows-10-version-build/).

 Some older versions of Windows 10 can also work, but you’ll have to manually install WSL.

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1815678/21290" target="_top" id="1815678">
  <img src="//a.impactradius-go.com/display-ad/21290-1815678" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://versadesk.pxf.io/i/5597632/1815678/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Enable Windows Subsystem for Linux

 In order to install the Linux bash shell on Windows 10, you first have to enable Windows Subsystem for Linux.

 You’ll know if WSL isn't enabled because you’ll run into the error: “The Windows Subsystem for Linux optional component is not enabled. Please enable it and try again.”

 Here’s how to enable WSL in Windows 10:

 You first need to get into Windows **Programs and Features**.

1. Open Windows 10 **Settings** and select **Apps**.
2. On the right side of the window, under **Related settings**, click on **Programs and Features**.

![Programs and Features option under the Related settings section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/program-and-features-option-in-settings.jpg)

 Once you’re in, click on **Turn Windows features on or off** on the left panel. Then scroll down and check the corresponding box to enable Windows Subsystem for Linux.

![Windows Subsystem for Linux option in Windows Features page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/enable-wsl-windows-10.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094480/7443" target="_top" id="2094480">
  <img src="//a.impactradius-go.com/display-ad/7443-2094480" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094480/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Click **OK** to save your changes and hit **Restart now** to finish the process.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/1062447/7443" target="_top" id="1062447">
  <img src="//a.impactradius-go.com/display-ad/7443-1062447" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/1062447/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Installing WSL on a Windows Machine

 With WSL enabled on your Windows device, you can [install Windows Subsystem for Linux](https://www.makeuseof.com/tag/linux-bash-shell-on-windows-10/). After that, you can install any supported Linux distro right inside your Windows PC. Choosing a [small, lightweight Linux distro](https://www.makeuseof.com/tag/linux-distro-space/) might be helpful.

 You can also [install a Linux desktop in Windows](https://www.makeuseof.com/tag/linux-desktop-windows-subsystem/) that gives you a graphical UI to work with.

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
<li><a href="https://youtube-sure.techidaily.com/harting-the-course-to-earnings-with-youtube-videos/"><u>[New] Charting the Course to Earnings with YouTube Videos</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-smart-editing-tricks-how-to-embed-dates-in-photo-albums-for-2024/"><u>[New] Smart Editing Tricks How to Embed Dates in Photo Albums for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-step-by-step-guide-mastering-ez-grabber-for-2024/"><u>[Updated] Step-by-Step Guide Mastering EZ Grabber for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-maximizing-chrome-multitasking-via-picture-in-picture-mode/"><u>2024 Approved Maximizing Chrome Multitasking via Picture in Picture Mode</u></a></li>
<li><a href="https://win-blog.techidaily.com/end-of-financial-functionality-era-for-microsoft-excel-users/"><u>End of Financial Functionality Era for Microsoft Excel Users</u></a></li>
<li><a href="https://windows11.techidaily.com/ending-dual-access-to-your-camera-error-0xa00f4243/"><u>Ending Dual Access to Your Camera (Error 0xA00F4243)</u></a></li>
<li><a href="https://windows11.techidaily.com/ensuring-privacy-with-best-windows-crypto-apps-152-chars/"><u>Ensuring Privacy with Best Windows Crypto Apps (152 Chars)</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-quickly-fix-bluetooth-not-working-on-itel-a60-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Quickly Fix Bluetooth Not Working on Itel A60 | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-leading-techniques-for-youtube-mpeg-migration/"><u>In 2024, Leading Techniques for YouTube MPEG Migration</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-pros-choice-top-15-luts-for-excellent-gopro-videos/"><u>In 2024, Pro's Choice Top 15 LUTs For Excellent GoPro Videos</u></a></li>
<li><a href="https://windows11.techidaily.com/personalize-your-digital-notepad-a-guide-to-windows-11-customization/"><u>Personalize Your Digital Notepad: A Guide to Windows 11 Customization</u></a></li>
<li><a href="https://windows11.techidaily.com/reconnecting-to-ea-servers-in-a-windows-environment/"><u>Reconnecting to EA Servers in a Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-to-prevent-not-working-on-your-pc/"><u>Swift Solutions to Prevent 'Not Working' On Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-picking-a-software-dependency-provider/"><u>The Ultimate Guide to Picking a Software Dependency Provider</u></a></li>
<li><a href="https://windows11.techidaily.com/tracking-windows-logins-identifying-successes-and-failures/"><u>Tracking Windows Logins: Identifying Successes & Failures</u></a></li>
<li><a href="https://games-able.techidaily.com/troubleshooting-for-undetected-games-on-steam-service/"><u>Troubleshooting for Undetected Games on Steam Service</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-registry-shortcomings-solutions/"><u>Unveiling Windows Registry Shortcomings: Solutions</u></a></li>
</ul></div>

