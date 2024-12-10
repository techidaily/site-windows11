---
title: "On/Off Switch: Controlling Windows' Energy-Saving Mode"
date: 2024-12-03T16:24:37.474Z
updated: 2024-12-10T17:08:27.953Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes On/Off Switch: Controlling Windows' Energy-Saving Mode"
excerpt: "This Article Describes On/Off Switch: Controlling Windows' Energy-Saving Mode"
keywords: Windows Sleep Control,Energy Saver Off/On,Power Management Switch,Eco-Mode Activation,Windows Energy Save,Utility Bypass Mode,Slumber Off/On Toggle
thumbnail: https://thmb.techidaily.com/412d065764cb0ba50733f600b7a0dabb6c2d4fd117a0cc25cd8642bbb251c9cc.png
---

## On/Off Switch: Controlling Windows' Energy-Saving Mode

 Your Windows laptop features a handy battery saver mode that allows you to stretch your device's battery life. Windows archives this by lowering the screen brightness, limiting background processes, and disabling certain visual effects and animations.

 Here we show you how to enable or disable battery saver mode on your Windows 10 or 11 laptop.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fo4lNZ84x9Q?si=WdcYPZp-9VJnZEnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Enable or Disable Battery Saver Mode Using Quick Settings

 The[Quick Settings panel in Windows](https://www.makeuseof.com/use-quick-settings-on-windows-11/) provides access to frequently used features such as Wi-Fi, Bluetooth, Airplane Mode, and others. You can also access this panel to turn the battery saver mode on or off quickly.

 Simply press**Win + A** to open the Quick Settings panel, and then click the**Battery saver** icon to enable or disable it.

![Enable or Disable Battery Saver in via Quick Settings Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-or-disable-battery-saver-in-via-quick-settings-panel.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E1ax-vnGdeo?si=bgTkOhOEwDTlRQE3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In case the Battery saver icon is missing, you can add it manually. Click the**pencil** icon at the bottom, and then select**Add > Battery saver** .

![Add Battery Saver Button to Quick Settings Panel in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/add-battery-saver-button-to-quick-settings-panel-in-windows.jpg)

## 2\. How to Enable or Disable Battery Saver Mode Using the Settings App

 Another way to turn the battery saver mode on or off in Windows is via the Settings app. To do so, use these steps:

1. Right-click on the**Start icon** and select**Settings** from the list.
2. In the**System** tab, click on**Power & battery** .
3. Under**Battery** , click on**Battery saver** to expand it.
4. Click the**Turn on now** button to enable battery saver mode.  
![Enable or Disable Battery Saver in via the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-or-disable-battery-saver-in-via-the-settings-app.jpg)

 If the battery saver mode is on, you will see the**Turn off now** button instead. Further, plugging your laptop into a power outlet will also disable the battery saver mode.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YwOwUI47FuU?si=NK7IEELjx7_SJSl2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. How to Configure the Battery Saver Mode to Turn On Automatically on Windows

 Don’t want to enable the battery saver mode manually all the time? No problem. You can configure Windows to activate battery saver mode automatically whenever the battery level drops below a specific percentage. To do so, you can use the Windows Settings app. Here are the steps you can follow.

1. Press**Win + I** to open the Settings app.
2. Navigate to**System > Power & battery** .
3. Click on**Battery saver** to expand it.
4. Click the drop-down menu next to**Turn battery saver on automatically at** and select your preferred battery level.  
![Configure the Battery Saver Mode to Turn On Automatically in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/configure-the-battery-saver-mode-to-turn-on-automatically-in-windows.jpg)

 You can also prevent Windows from enabling battery saver mode on its own by selecting**Never** . Alternatively, if you want the battery saver mode to be enabled at all times, choose**Always** instead.

 Although the Settings app is the most commonly used method for configuring the battery saver mode in Windows, it's not the only option available. You can also use a command-line tool like Command Prompt or Windows PowerShell to configure the battery saver mode to turn on automatically. Here are the steps for the same.

1. Use one of the[many ways to open Command Prompt or PowerShell](https://www.makeuseof.com/windows-open-command-prompt-powershell/) on your PC.
2. Type the following command in the console and press**Enter** .  
`powercfg /setdcvalueindex scheme_current sub_energysaver esbattthreshold <BatteryPercentage>`

 Replace**<BatteryPercentage>** in the above command with the percentage below which you want the battery saver mode to kick in automatically. Unlike the Settings app, you can specify a custom battery level percentage between 0 and 100 using the command line method.

![Configure the Battery Saver Mode to Turn On Automatically Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/configure-the-battery-saver-mode-to-turn-on-automatically-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 While PowerShell and Windows Terminal may look similar, they act very differently. Check our detailed guide to learn[the differences between PowerShell and Windows Terminal](https://www.makeuseof.com/windows-terminal-vs-powershell/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ME5-sAQJVE4?si=ZfcvJSnhQevWtjI0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Easily Enable or Disable Battery Saver Mode on Windows

 Battery saver mode in Windows can come in handy when you're away from a power source. However, it's important to note that leaving battery saver mode on all the time can impact certain features, such as notifications and background app sync. Hence, it's best to enable battery saver mode only when necessary.

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
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-step-by-step-periscope-broadcasting-101/"><u>[Updated] 2024 Approved Step-by-Step Periscope Broadcasting 101</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-castcritique-report/"><u>[Updated] CastCritique Report</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-the-ultimate-toolkit-for-editors-magix-video-pro-x-review/"><u>2024 Approved The Ultimate Toolkit for Editors Magix Video Pro X Review</u></a></li>
<li><a href="https://howto.techidaily.com/6-solutions-to-fix-error-505-in-google-play-store-on-lava-yuva-2-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Solutions to Fix Error 505 in Google Play Store on Lava Yuva 2 Pro | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-on-solving-icue-hardware-detection-issues-effectively/"><u>Expert Advice on Solving ICUE Hardware Detection Issues Effectively</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-maze-of-unacceptable-connections-on-windows/"><u>Navigating the Maze of Unacceptable Connections on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/sidestepping-windows-update-error-code-0x80242016/"><u>Sidestepping Windows Update Error Code 0X80242016</u></a></li>
<li><a href="https://win-answers.techidaily.com/step-by-step-solution-overcoming-the-tfla0002-issue-in-academic-testing/"><u>Step-by-Step Solution: Overcoming the TFLA0002 Issue in Academic Testing</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-fix-error-code-0x0001-in-geforce-experience/"><u>Strategies to Fix Error Code 0X0001 in GeForce Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-data-files-in-windows-11-using-ntfs-options/"><u>Streamline Your Data Files in Windows 11 Using NTFS Options</u></a></li>
<li><a href="https://win-great.techidaily.com/ultimate-image-to-pdf-converter-effortless-photo-compilation-into-professional-documents/"><u>Ultimate Image-to-PDF Converter: Effortless Photo Compilation Into Professional Documents</u></a></li>
<li><a href="https://windows11.techidaily.com/unplugging-troubles-stay-aware-of-power-save-mode/"><u>Unplugging Troubles: Stay Aware of Power Save Mode</u></a></li>
</ul></div>

