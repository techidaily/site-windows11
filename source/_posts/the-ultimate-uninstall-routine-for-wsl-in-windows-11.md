---
title: The Ultimate Uninstall Routine for WSL in Windows 11
date: 2025-01-06T16:27:58.159Z
updated: 2025-01-10T18:21:58.448Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S3Th6oa_isA?si=TTQ013BB9beUM4x6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Uninstall Windows Subsystem for Linux?

 WSL is a very handy tool that allows you to easily run Linux distros in a virtual environment on your Windows computer. Although it doesn't have much impact on storage space, if you have no interest in using Linux, there's no need to have it installed.

 There are also [good alternatives to WSL](https://www.makeuseof.com/dont-need-microsoft-windows-subsystem-for-linux/) for running Linux available, and you might decide to use one of those instead of the Microsoft solution. Not only would you not need WSL, but there is also a slight risk of conflict between the Windows Subsystem and your alternative choice.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E1ax-vnGdeo?si=bgTkOhOEwDTlRQE3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Remove All Installed Linux Distros on Windows

 This step won't be relevant to everyone, but if you have installed any Linux distros, you should remove them first. This helps to ensure that no files associated with the Linux installations remain on your computer when you uninstall WSL.

1. You can find your installed Linux distros listed with your other installed apps in **Settings > Apps > Installed Apps**.
2. Uninstall each of the Linux Distros, such as Ubuntu, in exactly the same way you would [uninstall any other Windows app](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/).

![Ubuntu in the Windows 11 apps list](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-remove.jpg)

 If the computer came to you with the apps already installed, you might not know what is or isn't a Linux distribution. Here are some of the [most common Linux distros](https://www.makeuseof.com/linux-distros-for-beginners-intermediate-and-advanced-users/), but you can also simply do a Google search for the name of the app you are unsure about.

 When all versions of Linux have been uninstalled, you can move on to the next step in the process.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LBCobAYzzcc?si=J3eSTQ3AdyxWAjGo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Uninstall the WSL Components

 With all versions of Linux removed, you can remove the WSL app and its related components. As with the previous step, you can remove WSL in the same way you would remove any other app.

 Go to **Settings > Apps > Apps & Features**. Scroll down to the bottom of your apps list to find Windows Subsystem for Linux. Click the **More** button and select **Uninstall**. On Windows 10, click on the app name and then click **Uninstall**.

![Uninstalling WSL components in Windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-components.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XVsiIO7hWOc?si=UvWnqxaI_yHwEr74" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you see any additional WSL components, such as the WSL update or WSLg Preview, uninstall these in the same way.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qbuund2HKOQ?si=NaGHqIrx8hSL7gWV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-helps.techidaily.com/new-leading-organizations-in-creating-immersive-vr-experiences-for-2024/"><u>[New] Leading Organizations in Creating Immersive VR Experiences for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-taking-screenshots-on-mac-5-methods-for-2024/"><u>[New] Taking Screenshots on Mac [5 Methods] for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-ideal-uavs-for-capturing-gopro-hd-footage/"><u>[Updated] In 2024, Ideal UAVs for Capturing GoPro HD Footage</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-issue-resolve-microsoft-windows-camera-error-0xa00f4292/"><u>Fixing the Issue: Resolve Microsoft Windows Camera Error 0xA00F4292</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-realme-gt-5-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 4 solution to get rid of pokemon fail to detect location On Realme GT 5 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/install-and-manage-packages-with-windows-package-manager-wpm/"><u>Install and Manage Packages with Windows Package Manager (WPM)</u></a></li>
<li><a href="https://windows11.techidaily.com/master-your-pictures-top-7-windows-photo-orgers/"><u>Master Your Pictures: Top 7 Windows Photo Orgers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/microsofts-breakthrough-swift-smart-team-tools/"><u>Microsoft's Breakthrough: Swift, Smart Team Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-mastering-w11-audio-recordings/"><u>Step-by-Step: Mastering W11 Audio Recordings</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-guide-to-usb-management-on-modern-systems/"><u>The Essential Guide to USB Management on Modern Systems</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/top-rated-robot-cleaners-comprehensive-reviews-and-testing-by-experts-techguide/"><u>Top-Rated Robot Cleaners: Comprehensive Reviews & Testing by Experts | TechGuide</u></a></li>
<li><a href="https://vp-tips.techidaily.com/ultimate-avi-video-compression-tool-shrink-and-enhance-your-videos-with-unmatched-clarity/"><u>Ultimate AVI Video Compression Tool: Shrink and Enhance Your Videos with Unmatched Clarity</u></a></li>
</ul></div>

