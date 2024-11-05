---
title: "Tailoring System Wake-Up: Shortening Boot Menu Hesitation Period"
date: 2024-11-04T10:39:20.486Z
updated: 2024-11-05T05:17:32.807Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tailoring System Wake-Up: Shortening Boot Menu Hesitation Period"
excerpt: "This Article Describes Tailoring System Wake-Up: Shortening Boot Menu Hesitation Period"
keywords: Quick Boot Windows,Reduce Boot Delay,Fast Start Windows,Shorter Boot Time,Accelerated Boot Window,Boot Menu Speed Up,Wake-Up Optimization
thumbnail: https://thmb.techidaily.com/fddafecbf8d052882c8613835d6b91422875b8a8af17428f6e6ddf368419a301.jpg
---

## Tailoring System Wake-Up: Shortening Boot Menu Hesitation Period

 When you turn on your dual-boot system, Windows waits for a while, allowing you to choose the operating system you want to load. However, the default wait time may be too short, giving you little time to decide.

 Fortunately, you can configure the wait time as per your choice. In this article, we'll explore four quick ways to change the boot menu timeout in Windows 11\. So, let's begin.

## 1\. Change Boot Menu Timeout Using the Settings App

 The quickest way to configure the boot menu timeout is via the Settings app. Here's a step-by-step instructions to do that:

1. Press the **Win + I** hotkey to open the **Settings app**.
2. Choose **System** from the left sidebar and **About** from the right pane.
3. Choose **System protection**.  
![System protection option in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-protection.jpg)
4. Switch to the **Advanced** tab and click the **Settings** button under the **Startup and Recovery** section.
5. Click the drop-down icon under the **Default operating system** option and choose your default OS.
6. Check the **Time to display list of operating systems** option and select the timeout value. The value can range from **0** to **999**.  
![Time to display list of operating systems option in System Protection window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/time-to-display-list-of-operating-systems-option.jpg)
7. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938677/19272" target="_top" id="1938677">
  <img src="//a.impactradius-go.com/display-ad/19272-1938677" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938677/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Change Boot Menu Timeout Using System Configuration

 The System Configuration app, aka msconfig, is a built-in Windows utility that lets you [control your system's startup programs](https://www.makeuseof.com/optimize-startup-programs-windows-11/) and services. You can also use it to adjust various system settings, including the boot menu timeout. To change the boot menu timeout using the System Configuration app, follow the below instructions:

1. Press the **Win** key to open the **Start Menu,** type **System Configuration** in the search bar, and select the same from the result.
2. Switch to the **Boot** tab.
3. Enter the value (seconds) in the **Timeout** section and check the **Make all boot settings permanent** option.  
![Timeout option in msconfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/timeout-option.jpg)
4. Click **Apply.**

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2002018/7443" target="_top" id="2002018">
  <img src="//a.impactradius-go.com/display-ad/7443-2002018" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2002018/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997680/19272" target="_top" id="1997680">
  <img src="//a.impactradius-go.com/display-ad/19272-1997680" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997680/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 That's it! From the next boot, the boot manager will appear for the specified duration of time.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130531/26400" target="_top" id="2130531">
  <img src="//a.impactradius-go.com/display-ad/26400-2130531" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130531/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-harnessing-the-power-of-short-videos-for-maximum-income/"><u>[Updated] 2024 Approved Harnessing the Power of Short Videos for Maximum Income</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-ultimate-collection-of-elite-cost-free-vfx-and-editing-websites/"><u>[Updated] The Ultimate Collection of Elite, Cost-Free VFX & Editing Websites</u></a></li>
<li><a href="https://windows11.techidaily.com/a-users-guide-to-windows-11-system-anomalies-analysis/"><u>A User’s Guide to Windows 11 System Anomalies Analysis</u></a></li>
<li><a href="https://windows11.techidaily.com/beat-the-blank-screen-blues-faster-input-in-windows-11/"><u>Beat the Blank Screen Blues: Faster Input in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/brighten-control-navigating-windows-11-display-settings/"><u>Brighten Control: Navigating Windows 11 Display Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-chromiums-firewall-connection-within-windows-safeguards/"><u>Enabling Chromium's Firewall Connection Within Windows Safeguards</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-xiaomi-redmi-13c-5g-phone-password-without-factory-reset-by-drfone-android/"><u>How to Unlock Xiaomi Redmi 13C 5G Phone Password Without Factory Reset?</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-optimal-vision-with-the-best-4k-monitors-1-10/"><u>In 2024, Optimal Vision with the Best 4K Monitors, #1-10</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-the-magnificent-art-of-pokemon-go-streaming-on-honor-x8b-drfone-by-drfone-virtual-android/"><u>In 2024, The Magnificent Art of Pokemon Go Streaming On Honor X8b? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-powershell-script-execution-policy-landscape/"><u>Navigating the PowerShell Script Execution Policy Landscape</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/rapid-growth-on-instagram-the-like-video-duo-power-for-2024/"><u>Rapid Growth on Instagram The Like-Video Duo Power for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/samsungs-latest-marvel-galaxy-z-fold-6-specs-news-and-availability-date-revealed/"><u>Samsung's Latest Marvel: Galaxy Z Fold 6 Specs, News, and Availability Date Revealed</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/silence-mastery-introducing-customizable-computing-chassis-and-luminescent-ventilators-for-bright-computer-enclosures/"><u>Silence Mastery: Introducing Customizable Computing Chassis & Luminescent Ventilators for Bright Computer Enclosures</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-reclaiming-standard-windows-11-search-preferences/"><u>Step-by-Step: Reclaiming Standard Windows 11 Search Preferences</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-restore-fn-key-brighness-in-windows-11/"><u>Steps to Restore Fn Key Brighness in Windows 11</u></a></li>
</ul></div>

