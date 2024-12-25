---
title: "Unlocking the Power of Testing: Enable Sandbox in Win 11"
date: 2024-12-20T16:58:31.616Z
updated: 2024-12-25T17:14:33.268Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlocking the Power of Testing: Enable Sandbox in Win 11"
excerpt: "This Article Describes Unlocking the Power of Testing: Enable Sandbox in Win 11"
keywords: Win 11 Sandbox Tests,Sandbox Feature Win11,Unlock Win11 Testing,Enable Win11 Sandbox,Win11 Test Environment,Powerful Win11 Sandbox,Sandbox in Win11 Pro
thumbnail: https://thmb.techidaily.com/0791bf71ffcd0caa089c5eb4acb0659b94a16305034b7e133b158f74795a132b.jpg
---

## Unlocking the Power of Testing: Enable Sandbox in Win 11

 Microsoft Windows 11 features multiple virtualization solutions out of the box. While Hyper-V is an excellent tool, Windows Sandbox is an easy alternative to Windows virtual machines. It lets you run untrusted apps in an isolated environment without the hassle of setting up a complete virtualization tool.

 Unfortunately, Windows Sandbox is not available on the Home edition of the OS. If you are running the Pro, Enterprise, and Education edition, here is how to enable and set up Windows Sandbox in Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oeSN3u4fO9M?si=Ua3Hzcil6u6akDgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Set Up Windows Sandbox in Windows 11

 Windows Sandbox is an optional feature, which means you'll have to install it from the Optional features section. You can[add and remove optional features from the Windows Features dialog](http://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) . Alternatively, you can use PowerShell or Command Prompt for a swift installation of Windows Sandbox.

 While the setup process is easier, your computer must meet some system requirements. Windows 11 Pro, Education, or Enterprise running computers with virtualization support are Windows Sandbox compatible. In most cases,[if your system can run Windows Hyper-V](https://www.makeuseof.com/windows-11-enable-hyper-v/) , it should also run Windows Sandbox.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bXmwwSmYqq4?si=Bb-eJfLnlpeeClyt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Enable Windows Sandbox Using the Windows Features Dialog

 You can install Windows Sandbox using the Windows Features dialog. This dialog houses most of the optional Windows features that are ready to be installed on your PC.

 Follow these steps to install Windows Sandbox using the Windows Features dialog:

1. Press**Win + R** to open**Run** .
2. Type**appwiz.cpl** and click**OK** to open**Control Panel.**
3. In the left panel, click on**Turn Windows features on or off.**  
![control panel turn windows features on or off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/control-panel-turn-windows-features-on-or-off.jpg)
4. In the**Turn Windows features on or off dialog** , scroll down and locate**Windows Sandbox.**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Check the**Windows Sandbox** option and click**OK** .  
![enable Windows sandbox turn windows features on or off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-Windows-sandbox-turn-windows-features-on-or-off.jpg)
6. Windows will search for the files and install the required dependencies to run Windows Sandbox scenarios. Once the changes are applied, close the Windows features dialog and restart your PC.
7. After the restart, press**Win + S** to open**Windows search.**
8. Type**sandbox** and click on**Windows Sandbox** from the search result to launch the virtualization tool.

## 3\. Install Windows Sandbox Using PowerShell

![enable windows sandbox powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-windows-sandbox-powershell.jpg)

 You can use the Enable WindowsOptionalFeature command in PowerShell to install Windows Sandbox in Windows. This method is useful if you find the sandbox option greyed out or unable to install it from the Windows Feature dialog.

To install Windows Sandbox using PowerShell:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Windows Terminal (Admin)** to open the Windows Terminal with administrative privilege. Since PowerShell is assigned as the default profile upon launch, you can execute your PowerShell cmdlets straight away in Windows Terminal.
3. In the Windows Terminal window, copy and paste the following command and press Enter:  
Enable-WindowsOptionalFeature -Online -FeatureName "Containers-DisposableClientVM" -All
4. If no error occurs, Windows will install the required files to enable Windows Sandbox.
5. Once done, press**Y** and hit**Enter** to restart your PC.
6. After the restart, you can launch Windows Sandbox from Windows Search.

## 3\. Install Windows SandBox Using Command Prompt

![enable windows sandbox command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-windows-sandbox-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Deployment Image Servicing and Management (DISM) is a command-line utility that facilitates the installation of optional features using the Command Prompt. To install Windows Sandbox, you will need to use the Enable-Feature command in Command Prompt. Here's how to do it.

1. Press**Win + R** to open**Run** .
2. Type**cmd** in the**Run** dialog. Press and hold**Ctrl + Shift** and click**OK** to open Command Prompt as administrator.
3. In the Command Prompt, type the following command and press**Enter** :  
`dism /online /Enable-Feature /FeatureName: "Containers-DisposableClientVM" -All`
4. Wait for the process to complete. Once done, press**Y** and**Enter** to restart your PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3UyJuZYzjt0?si=W87GeyzVKVORAk7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Use Windows Sandbox

![Windows Sandbox Open](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Windows-Sandbox-Open.jpg)

 Now that you have Windows Sandbox installed, you can start using it to test untrusted apps in isolation. To launch the app, press**Win + S** to open**Windows Search** and type**Windows Sandbox.** Click on the app from the search result to open it.

 Upon its launch, Windows Sandbox looks like a lightweight version of your Windows machine. You can copy files from your host system or download them from the Internet using the built-in web browser. Any actions you perform in the sandbox will not affect your host system.

 Once the testing is complete, close the Sandbox and click**OK** to confirm the action. Unlike a VM, Sandbox will delete all the data (including apps and files) upon exit. So, you'll get a clean, isolated environment running the same Windows OS build as your host machine each time.

## Set Up and Use Windows Sandbox in Windows 11

 Windows Sandbox provides an excellent way to test apps and files in an isolated environment without the hassle of setting up a virtual machine. While the virtual machines have distinct advantages, Sandbox is lighter, faster, and loads a fresh copy of Windows OS each time it's run.

 Windows 11 Home users, however, have missed out on this excellent feature. But if you must use a sandbox, consider using third-party alternatives such as Sandboxie Plus and SHADE Sandbox. These alternatives offer a similar set of functionalities with no complicated setup involved.

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
<li><a href="https://digital-screen-recording.techidaily.com/new-conveniently-connect-friends-across-os-platforms-using-skype-chats/"><u>[New] Conveniently Connect Friends Across OS Platforms Using Skype Chats</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-unveil-the-secrets-to-excellent-youtube-thumbnails/"><u>[New] In 2024, Unveil the Secrets to Excellent YouTube Thumbnails</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-best-practice-mp4-director-to-fb/"><u>[Updated] Best Practice MP4 Director to FB</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-organization-restricted-options-errors-in-windows-11-os/"><u>Fixing Organization-Restricted Options Errors in Windows 11 OS</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-honor-x50iplus-by-drfone-android/"><u>In 2024, The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On Honor X50i+</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-the-ultimate-insights-for-successful-short-video-creation/"><u>In 2024, The Ultimate Insights for Successful Short Video Creation</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ios-18-unveiled-top-6-ai-enhancements-for-iphone-devices-and-future-updates-to-watch-out-for/"><u>IOS 18 Unveiled: Top 6 AI Enhancements for iPhone Devices & Future Updates to Watch Out For!</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-pro-grade-animation-top-software-picks-for-mac-and-windows-users/"><u>New Pro-Grade Animation Top Software Picks for Mac and Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/optimal-windows-solutions-for-video-file-editing-and-conversion/"><u>Optimal Windows Solutions for Video File Editing & Conversion</u></a></li>
<li><a href="https://discover-data.techidaily.com/ripristino-della-partizione-primaria-eliminata-per-errore-su-windows-10/"><u>Ripristino Della Partizione Primaria Eliminata per Errore Su Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/screen-separation-strategies-wallpapers-per-monitor-windows-style/"><u>Screen Separation Strategies: Wallpapers per Monitor, Windows Style</u></a></li>
<li><a href="https://vp-tips.techidaily.com/stegvisu-diskord-skarmshandling-pa-pc-och-mobil-plattformer/"><u>Stegvisu Diskord-Skärmshandling På PC Och Mobil Plattformer</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-printer-offline-on-windows-11/"><u>Understanding 'Printer Offline' On Windows 11</u></a></li>
</ul></div>

