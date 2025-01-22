---
title: Adjusting Low-Power Options for Better Battery Life
date: 2025-01-18T19:23:26.673Z
updated: 2025-01-22T19:22:23.632Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Low-Power Options for Better Battery Life
excerpt: This Article Describes Adjusting Low-Power Options for Better Battery Life
keywords: Battery Power Settings,Energy Saving Mode,Optimize Battery Use,Efficient Charging Techniques,Low-Power System Tweaks,Enhance Battery Life,Improve Power Management
thumbnail: https://thmb.techidaily.com/98061f90f0702266772c41039bf7505ea26afb88709675b4845f86d9c07123c1.jpg
---

## Adjusting Low-Power Options for Better Battery Life

 Your Windows laptop features a handy battery saver mode that allows you to stretch your device's battery life. Windows archives this by lowering the screen brightness, limiting background processes, and disabling certain visual effects and animations.

 Here we show you how to enable or disable battery saver mode on your Windows 10 or 11 laptop.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Enable or Disable Battery Saver Mode Using Quick Settings

 The [Quick Settings panel in Windows](https://www.makeuseof.com/use-quick-settings-on-windows-11/) provides access to frequently used features such as Wi-Fi, Bluetooth, Airplane Mode, and others. You can also access this panel to turn the battery saver mode on or off quickly.

 Simply press**Win + A** to open the Quick Settings panel, and then click the**Battery saver** icon to enable or disable it.

![Enable or Disable Battery Saver in via Quick Settings Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-or-disable-battery-saver-in-via-quick-settings-panel.jpg)

 In case the Battery saver icon is missing, you can add it manually. Click the**pencil** icon at the bottom, and then select**Add > Battery saver** .

![Add Battery Saver Button to Quick Settings Panel in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/add-battery-saver-button-to-quick-settings-panel-in-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0pSRlspzW-A?si=A82G3Yxwj_31cKDq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/H2cXnI9oOvM?si=3nz2sBB124ln-83T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Enable or Disable Battery Saver Mode Using the Settings App

 Another way to turn the battery saver mode on or off in Windows is via the Settings app. To do so, use these steps:

1. Right-click on the**Start icon** and select**Settings** from the list.
2. In the**System** tab, click on**Power & battery** .
3. Under**Battery** , click on**Battery saver** to expand it.
4. Click the**Turn on now** button to enable battery saver mode.  
![Enable or Disable Battery Saver in via the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-or-disable-battery-saver-in-via-the-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/TJCye_oCTTw?si=6bVyBphcSgSFdyuq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the battery saver mode is on, you will see the**Turn off now** button instead. Further, plugging your laptop into a power outlet will also disable the battery saver mode.

## 3\. How to Configure the Battery Saver Mode to Turn On Automatically on Windows

 Don’t want to enable the battery saver mode manually all the time? No problem. You can configure Windows to activate battery saver mode automatically whenever the battery level drops below a specific percentage. To do so, you can use the Windows Settings app. Here are the steps you can follow.

1. Press**Win + I** to open the Settings app.
2. Navigate to**System > Power & battery** .
3. Click on**Battery saver** to expand it.
4. Click the drop-down menu next to**Turn battery saver on automatically at** and select your preferred battery level.  
![Configure the Battery Saver Mode to Turn On Automatically in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/configure-the-battery-saver-mode-to-turn-on-automatically-in-windows.jpg)

 You can also prevent Windows from enabling battery saver mode on its own by selecting**Never** . Alternatively, if you want the battery saver mode to be enabled at all times, choose**Always** instead.

 Although the Settings app is the most commonly used method for configuring the battery saver mode in Windows, it's not the only option available. You can also use a command-line tool like Command Prompt or Windows PowerShell to configure the battery saver mode to turn on automatically. Here are the steps for the same.

1. Use one of the [many ways to open Command Prompt or PowerShell](https://www.makeuseof.com/windows-open-command-prompt-powershell/) on your PC.
2. Type the following command in the console and press**Enter** .  
`powercfg /setdcvalueindex scheme_current sub_energysaver esbattthreshold <BatteryPercentage>`

 Replace**<BatteryPercentage>** in the above command with the percentage below which you want the battery saver mode to kick in automatically. Unlike the Settings app, you can specify a custom battery level percentage between 0 and 100 using the command line method.

![Configure the Battery Saver Mode to Turn On Automatically Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/configure-the-battery-saver-mode-to-turn-on-automatically-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MmTJlcwgyrQ?si=x3hba82M0tT57fj7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 While PowerShell and Windows Terminal may look similar, they act very differently. Check our detailed guide to learn [the differences between PowerShell and Windows Terminal](https://www.makeuseof.com/windows-terminal-vs-powershell/) .

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
<li><a href="https://twitter-clips.techidaily.com/new-2024-approved-visualizing-tweet-reactions-a-complete-twitch-tale-for-23/"><u>[New] 2024 Approved Visualizing Tweet Reactions - A Complete Twitch-Tale for '23</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-economical-videography-for-extreme-sports-enthusiasts-for-2024/"><u>[Updated] Economical Videography for Extreme Sports Enthusiasts for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/10-easy-steps-for-a-working-windows-mouse/"><u>10 Easy Steps for a Working Windows Mouse</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-secure-your-remote-sessions-with-these-tools/"><u>2024 Approved Secure Your Remote Sessions with These Tools</u></a></li>
<li><a href="https://video-capture.techidaily.com/1726028590911-mp4mp3/"><u>次世代デバイス用MP4、MP3コンバーターサイト: あなたの追加リクエストに対するおすすめ</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-the-incorrect-identifier-message-in-windows-11/"><u>Addressing the 'Incorrect Identifier' Message in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/arrows-at-a-standstill-try-these-remedies/"><u>Arrows at a Standstill? Try These Remedies</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-winos-gain-control-over-applications-browsing/"><u>Decoding WinOS: Gain Control over Applications, Browsing</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-webp-image-save-in-google-chrome-windows-edition/"><u>Disabling WebP Image Save in Google Chrome, Windows Edition</u></a></li>
<li><a href="https://driver-install.techidaily.com/eliminating-problems-samsung-ssd-and-windows-synergy/"><u>Eliminating Problems: Samsung SSD and Windows Synergy</u></a></li>
<li><a href="https://win-blog.techidaily.com/get-past-the-stalled-loading-strategies-to-surpass-the-90-mark-in-phasmophobia-2024-solution/"><u>Get Past the Stalled Loading: Strategies to Surpass the 90% Mark in Phasmophobia (2024 Solution)</u></a></li>
<li><a href="https://fox-ssl.techidaily.com/revolutionize-your-approach-to-crisis-handling-in-2amo-with-cutting-edge-massmail-software-2009/"><u>Revolutionize Your Approach to Crisis Handling in 2Amo With Cutting-Edge MassMail Software (2009)</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/top-4-ways-to-trace-apple-iphone-7-plus-location-drfone-by-drfone-virtual-ios/"><u>Top 4 Ways to Trace Apple iPhone 7 Plus Location | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/unstuck-from-intel-drivers-and-support-assistance-problems-expert-fixes-for-pc-users/"><u>Unstuck From Intel Drivers and Support Assistance Problems: Expert Fixes for PC Users</u></a></li>
</ul></div>

