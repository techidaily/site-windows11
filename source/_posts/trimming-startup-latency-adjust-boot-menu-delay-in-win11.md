---
title: "Trimming Startup Latency: Adjust Boot Menu Delay in Win11"
date: 2024-12-07T17:22:50.705Z
updated: 2024-12-10T16:14:14.215Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Trimming Startup Latency: Adjust Boot Menu Delay in Win11"
excerpt: "This Article Describes Trimming Startup Latency: Adjust Boot Menu Delay in Win11"
keywords: Win11 Boot Speed,Reduce Startup Time,Minimize Boot Lag,Optimize Windows Boot,Trim System Latency,Accelerate OS Launch,Delay Adjustment Win11
thumbnail: https://thmb.techidaily.com/267d92bf94270151f5bfac8360b3ac61e42f156ac8997243316d48f1378e1df1.jpg
---

## Trimming Startup Latency: Adjust Boot Menu Delay in Win11

 When you turn on your dual-boot system, Windows waits for a while, allowing you to choose the operating system you want to load. However, the default wait time may be too short, giving you little time to decide.

 Fortunately, you can configure the wait time as per your choice. In this article, we'll explore four quick ways to change the boot menu timeout in Windows 11\. So, let's begin.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l4R7_qNIQvY?si=2zJOPfEcm6_3udzn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Change Boot Menu Timeout Using the Settings App

 The quickest way to configure the boot menu timeout is via the Settings app. Here's a step-by-step instructions to do that:

1. Press the **Win + I** hotkey to open the **Settings app**.
2. Choose **System** from the left sidebar and **About** from the right pane.
3. Choose **System protection**.  
![System protection option in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-protection.jpg)
4. Switch to the **Advanced** tab and click the **Settings** button under the **Startup and Recovery** section.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xa2_mFu-obA?si=_xDGF1pv-dnuaDOr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Click the drop-down icon under the **Default operating system** option and choose your default OS.
6. Check the **Time to display list of operating systems** option and select the timeout value. The value can range from **0** to **999**.  
![Time to display list of operating systems option in System Protection window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/time-to-display-list-of-operating-systems-option.jpg)
7. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Change Boot Menu Timeout Using System Configuration

 The System Configuration app, aka msconfig, is a built-in Windows utility that lets you [control your system's startup programs](https://www.makeuseof.com/optimize-startup-programs-windows-11/) and services. You can also use it to adjust various system settings, including the boot menu timeout. To change the boot menu timeout using the System Configuration app, follow the below instructions:

1. Press the **Win** key to open the **Start Menu,** type **System Configuration** in the search bar, and select the same from the result.
2. Switch to the **Boot** tab.
3. Enter the value (seconds) in the **Timeout** section and check the **Make all boot settings permanent** option.  
![Timeout option in msconfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/timeout-option.jpg)
4. Click **Apply.**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Click **Yes** to confirm your changes.  
![Yes option in msconfig window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/yes-option-1.jpg)
6. Choose the **Restart** button.

## 3\. Change Boot Menu Timeout Using the Command Prompt

 If you're an advanced Windows user, you can use Command Prompt to configure the boot menu timeout on your Windows PC. Here's how:

1. Open the Start Menu, type **Command Prompt** in the search bar, and choose **Run as administrator** from the right pane. If this method doesn't work, check out other ways to [launch Command Prompt in Windows](https://www.makeuseof.com/windows-11-open-command-prompt/).
2. In the elevated Command Prompt window, type the following command and press Enter. This will display the current time for which the boot menu appears.  
`bcdedit`
3. Type the following command and press Enter to change the timeout. Make sure to replace **`SECONDS`**with the new timeout.  
`bcdedit /timeout SECONDS`  
![Timeout change command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/timout-change-command.jpg)

 That's it! From the next boot, the boot manager will appear for the specified duration of time.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GyfJUhsz_AY?si=x2HjoLX1B89oEPgZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Change Boot Menu Timeout Using the Boot Options

 Another efficient way to configure the boot menu timeout is through the Boot Manager. The Boot Manager, also known as the Boot Loader, is responsible for launching your operating system when you turn on your computer. Not only that, it enables you to select a specific operating system if you are using multiple operating systems on your device.

 To modify the boot menu timeout through the Boot Manager, follow these instructions:

1. Open the Start Menu, click the **Power icon** and choose **Restart** from the context menu. If this method doesn't work, try any other [ways to restart your Windows PC](https://www.makeuseof.com/windows-restart-methods/).
2. In the Boot Manager, click on **Change defaults or choose other options**.  
![Change defaults or choose other options in the Boot menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-defaults-or-choose-other-options.jpg)
3. Select the **Change the timer** option.  
![Change the timer option in the Boot menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-the-timer.jpg)
4. Choose a time between the given options.  
![Choose time in the Boot Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/choose-time.jpg)

## Control Your System Boot Menu on Windows

 Optimizing the boot menu timeout in Windows is a simple yet effective way to manage your system's startup time. By adjusting the duration for which the boot menu appears, you can ensure that you have adequate time to select your preferred operating system.

 Fortunately, you can configure the wait time as per your choice. In this article, we'll explore four quick ways to change the boot menu timeout in Windows 11\. So, let's begin.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://digital-screen-recording.techidaily.com/new-audiovisual-success-recording-gotomeetings-easily/"><u>[New] Audiovisual Success Recording GoToMeetings Easily</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-the-blueprint-for-successful-biographies-top-tips-and-techniques-from-experts/"><u>[Updated] The Blueprint for Successful Biographies Top Tips & Techniques From Experts</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/android-guide-enhance-your-video/"><u>Android Guide Enhance Your Video</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/clearance-checking-guidelines-for-pre-upload-to-tiktok/"><u>Clearance-Checking Guidelines for Pre-Upload to TikTok</u></a></li>
<li><a href="https://blog-min.techidaily.com/easy-fixes-for-when-hulu-wont-work-a-comprehensive-guide-to-resolving-streaming-troubles/"><u>Easy Fixes for When Hulu Won't Work: A Comprehensive Guide to Resolving Streaming Troubles</u></a></li>
<li><a href="https://windows11.techidaily.com/invisibly-erase-language-line-from-windows-11-ui/"><u>Invisibly Erase Language Line From Windows 11 UI</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-installation-woes-clipchamp-and-windows-11-guide/"><u>Mastering Installation Woes: ClipChamp and Windows 11 Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/modifying-webcam-activity-alert-settings-for-win11/"><u>Modifying Webcam Activity Alert Settings for Win11</u></a></li>
<li><a href="https://vp-tips.techidaily.com/movavi-converter-mudando-formatos-de-imagem-online-de-graca-bmp-para-outros/"><u>Movavi Converter: Mudando Formatos De Imagem Online De Graça - BMP Para Outros</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-the-maze-of-windows-security-faults/"><u>Navigating Through the Maze of Windows Security Faults</u></a></li>
<li><a href="https://windows11.techidaily.com/reawaken-your-computers-usb-a-quick-fix-guide-windows/"><u>Reawaken Your Computer's USB: A Quick Fix Guide, Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-java-not-installing-issues-on-windows-systems/"><u>Remedying Java Not Installing Issues on Windows Systems</u></a></li>
<li><a href="https://techidaily.com/samsung-data-retrieval-tool-restore-lost-data-from-samsung-by-fonelab-android-recover-data/"><u>Samsung Data Retrieval tool – restore lost data from Samsung</u></a></li>
<li><a href="https://windows11.techidaily.com/skip-suspended-pop-ups-from-non-adobe-software/"><u>Skip Suspended Pop-Ups From Non-Adobe Software</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-tips-for-stabilizing-your-dragons-dogma-2-pc-gameplay-experience/"><u>Troubleshooting Tips for Stabilizing Your Dragon's Dogma 2 PC Gameplay Experience</u></a></li>
</ul></div>

