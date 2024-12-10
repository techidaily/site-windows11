---
title: Harnessing the Power of Linux Inside a Windows OS
date: 2024-12-08T18:04:58.965Z
updated: 2024-12-10T19:13:17.732Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Harnessing the Power of Linux Inside a Windows OS
excerpt: This Article Describes Harnessing the Power of Linux Inside a Windows OS
keywords: Linux on WinOS,Windows-Linux Integration,Linux in Windows Environment,Cross-OS Development with Linux,Linux Tools for Windows Users,Windows Supporting Linux Features,Enhancing OS Capabilities with Linux
thumbnail: https://thmb.techidaily.com/aca28fbc907b3b2134a063785955f99d7ee87845f83996484c29a6f763ca253a.jpg
---

## Harnessing the Power of Linux Inside a Windows OS

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/JlX-G8rBs1w?si=iIhUoWAq5x3YK9rA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/c17xsnbinCQ?si=xHKslFgC3QbxY4qW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’re in, click on **Turn Windows features on or off** on the left panel. Then scroll down and check the corresponding box to enable Windows Subsystem for Linux.

![Windows Subsystem for Linux option in Windows Features page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/enable-wsl-windows-10.jpg)

 Click **OK** to save your changes and hit **Restart now** to finish the process.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Installing WSL on a Windows Machine

 With WSL enabled on your Windows device, you can [install Windows Subsystem for Linux](https://www.makeuseof.com/tag/linux-bash-shell-on-windows-10/). After that, you can install any supported Linux distro right inside your Windows PC. Choosing a [small, lightweight Linux distro](https://www.makeuseof.com/tag/linux-distro-space/) might be helpful.

 You can also [install a Linux desktop in Windows](https://www.makeuseof.com/tag/linux-desktop-windows-subsystem/) that gives you a graphical UI to work with.

## WSL1 or WSL2: Which Is Better For You?

 WSL2 is an upgraded version of Windows Subsystem for Linux and is now the default when installing a Linux distribution in Windows. It works with Windows 11 or Windows 10, Version 1903, Build 18362 or higher.

 There are a few differences between the two versions of WSL; chiefly, WSL2 offers better performance in addition to support for full system call compatibility and IPv6 support. Also, WSL2 uses a full Linux kernel inside a managed virtual machine (VM), so you don’t have to set up and manage a VM to run a Linux distro.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zmXpl6irBYk?si=BXjGpQr6PXFcqhCI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-web.techidaily.com/024-approved-the-complete-youtube-editors-toolkit-for-post-publish-adjustments/"><u>[New] 2024 Approved The Complete YouTube Editor's Toolkit for Post-Publish Adjustments</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-photo-perfection-top-6-iphone-utilities-to-exclude-unwanted-elements/"><u>2024 Approved Photo Perfection Top 6 iPhone Utilities to Exclude Unwanted Elements</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/artists-claim-vindication-against-openaimeta-in-court/"><u>Artists Claim Vindication: Against OpenAI/Meta in Court</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-additional-views-in-win-11s-context-menu/"><u>Eliminating Additional Views in Win 11'S Context Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-cannot-open-issue-with-files-in-office-365-mail/"><u>Fixing 'Cannot Open' Issue with Files in Office 365 Mail</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-automatically-shut-down-a-windows-10-and-11-pc-when-its-idle/"><u>How to Automatically Shut Down a Windows 10 and 11 PC When It's Idle</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/impact-of-crop-residue-on-soil-microbial-composition-and-activity-after-harvest/"><u>Impact of Crop Residue on Soil Microbial Composition and Activity After Harvest</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-oppo-a1-5g-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>In 2024, How to Cast Oppo A1 5G to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/quickly-locate-new-windows-files-and-folders/"><u>Quickly Locate New Windows Files and Folders</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-xiaomi-redmi-note-12-pro-5g-drfone-by-drfone-virtual-android/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Xiaomi Redmi Note 12 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/simple-steps-switching-your-display-orientation-on-windows-11/"><u>Simple Steps: Switching Your Display Orientation on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-without-drive-letters-analyzing-problems-and-proposed-solutions/"><u>Windows Without Drive Letters: Analyzing Problems and Proposed Solutions</u></a></li>
</ul></div>

