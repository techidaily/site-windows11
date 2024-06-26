---
title: How to Fix the Xbox Game Pass 0X800700e9 Error in Windows 11 & 11
date: 2024-06-25T12:14:51.149Z
updated: 2024-06-26T12:14:51.149Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the Xbox Game Pass 0X800700e9 Error in Windows 11 & 11
excerpt: This Article Describes How to Fix the Xbox Game Pass 0X800700e9 Error in Windows 11 & 11
keywords: Fix Xbox Game Pass 0X800700E9 Error,Resolve Xbox Game Pass Error,Xbox Game Pass Windows Fix,Clear Xbox Game Pass Error Win11,Troubleshoot Game Pass Error,Stop Xbox Game Pass 0X8007 Error,Repair Game Pass Issue Windows 11
thumbnail: https://thmb.techidaily.com/3b3b313aac4422406d268b9ec86a52f71522ac5dfd6eae7e41b861cd70dad021.png
---

## How to Fix the Xbox Game Pass 0X800700e9 Error in Windows 11 & 11

 The Xbox Game Pass is a popular Microsoft subscription service for games. However, some users encounter a 0x800700e9 error when they try to download and install Xbox Game Pass titles via the Xbox app or Microsoft Store. The 0x800700e9 error code message says “Something unexpected happened,” which provides no clue as to how to resolve that issue.

 Users can’t download and install Xbox Game Pass content because of error 0x800700e9\. However, you can fix error 0x800700e9 with these potential resolutions.

## 1\. Run the Microsoft Store App Troubleshooter

 The Windows Store App troubleshooter might help fix the error 0x800700e9\. This is how you can access the Windows Store App troubleshooter in Windows 11:

1. Use one of the many[ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Click the**Troubleshoot** box that has a spanner icon.
3. Next, click**Other-troubleshooters** to access the Settings app’s list of troubleshooting tools.
4. Select**Run** for activating the Windows Store Apps.  
![The Run button for the Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-button-for-windows-store-apps-troubleshooter.jpg)
5. Apply any suggestions the troubleshooter provides.

 The Windows 10 troubleshooters are available within the**Update & Security** category of Settings. Click the**Troubleshoot** tab in that category and select**Additional troubleshooters** . Then you can select Windows Store Apps from there and click**Run** to access the tool.

## 2\. Turn Delivery Optimization On in Settings

 Delivery Optimization is a service that enables Windows Update downloads from other PCs. Error 0x800700e9 often arises when Delivery Optimization is disabled in Windows. You can turn on Delivery Optimization via Settings like this:

1. Open the**Windows Update** tab in Settings.
2. Click**Advanced options** to view more settings.
3. Select the**Delivery Optimization** navigation option.  
![The Delivery Optimization navigation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/delivery-optimization-navigation-option.jpg)
4. Turn on the**Allow downloads from other PCs** option to enable Delivery Optimization.  
![The Allow downloads from other PCs option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/allow-downloads-from-other-pcs-option.jpg)
5. Click the**Devices on my local network** radio button.

 You can enable Delivery Optimization in Windows 10’s Settings app much the same. However, you’ll need to select the**Windows Update** category. Then click the**Deliver Optimization** tab in the**Windows Update** category to access and turn on the same**Allow downloads from other PCs** setting.

## 3\. Enable the Delivery Optimization and BITS Services

 Some Xbox Game Pass users have resolved error 0x800700e9 by enabling and running the Delivery Optimization and BITS services. You can enable and start those services via that app as follows:

1. To access Run, press**Win + R** .
2. Type**services.msc** inside Run’s**Open** command box.
3. Select**OK** to open Services.
4. Double-click the Delivery Optimization service.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/services-window2.jpg)
5. Select**Start** if it’s not running.
6. Click**Automatic** on Delivery Optimization’s**Startup type** menu.  
![The Delivery Optimization Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/delivery-optimization-properties-window.jpg)
7. Select**Apply** \>**OK** to save the service’s new settings.
8. Repeat steps four to seven for the Background Intelligent Transfer service.

 If the services are already running, try restarting them. Right-click the services and select their**Stop** options. Then you can start those services again by right-clicking them and selecting**Restart** .

## 4\. Enable Delivery Optimization via the Windows Registry

 If the above methods didn't work for you, try enabling Delivery Optimization service by editing the registry. You can back up the registry or set up a restore point before editing the registry if you want to be extra careful. To apply this potential solution, edit the**DoSvc** key like this:

1. First, bring up Registry Editor, which you can open with one of the methods in our guide on[how to open Regedit](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Click inside the address bar at the top of Registry Editor and erase the current key location.
3. Input this**DoSvc** key location in the address bar and hit**Return** :  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\DoSvc`  
![The DoSvc key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dovsc-key.jpg)
4. Select the**DoSvc** key, and right-click the**Start** DWORD to select**Modify** .  
![The Modify option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/modify-option.jpg)
5. Input**3** in the**Value** box and click**OK** .  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/start-dword-key.jpg)
6. Exit Regedit, and restart the PC.

## 5\. Reset or Repair the Xbox App

 Many users go through the Xbox app to get at their Xbox Game Pass titles on Windows. As such, you might be able to fix error 0x800700e9 by selecting**Reset and Repair** options for the Xbox app inside Settings.

 Check out our guide on[resetting apps in Windows 11 and 10](https://www.makeuseof.com/windows-reset-app/) to clear the Xbox app’s data. The**Repair** option for the Xbox app in Settings is available just above its**Reset** button.

![The Reset option for the Xbox app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reset-option.jpg)

## 6\. Reset the Microsoft Store Cache

 A corrupted Microsoft Store cache data can cause download and installation issues to arise for apps available on Microsoft’s online store. So, resetting the Store’s cache could be another potential solution for the 0x800700e9 error. Try resetting Microsoft Store’s cache in the following steps:

1. Bring up the Windows Search by clicking the magnifying glass or**Search** box on your taskbar.
2. Type**WSReset.exe** within the search box to find that Run command file.
3. Click**WSReset.exe** to run the command.  
![The wsreset.exe Run command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/wsreset-exe-command.jpg)
4. Wait for MS Store to open automatically, and then try downloading Xbox Game Pass titles again.

## 7\. Reinstall the Microsoft Store

 Reinstalling the Microsoft Store can fix deeper issues with that app that could be causing error 0x800700e9\. Although you can’t select to uninstall Microsoft Store, you can still reinstall that app with a PowerShell command. Here are the steps for reinstalling the Microsoft Store via PowerShell:

1. Bring up Run with the**Win + R** keyboard shortcut, and input**PowerShell** within the text box.
2. Right-click PowerShell to bring up a context menu, and select the**Run as administrator** option.
3. Execute this PowerShell command for reinstalling Microsoft Store:  
`Get-AppxPackage -allusers Microsoft.WindowsStore | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall Microsoft Store command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reinstall-microsoft-store-command.jpg)
4. Wait for the command to finish, and then exit the command app.

## 8\. Reset Your Network

![The Network reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-reset-option.jpg)

 Error 0x800700e9 can also sometimes occur because of network issues. Performing a network reset is a good way to troubleshoot issues in this area; however, do note that this will restore your network components to their factory defaults and erase your Wi-Fi and Ethernet connections.

 Have a look at our[how to reset your network settings on Windows](https://www.makeuseof.com/reset-network-settings-windows-11/) guide for details about how to apply this troubleshooting method.

## Enjoy Your Xbox Game Pass Games Again

 Fortunately, you don’t have to cancel your Xbox Game Pass subscription because of error 0x800700e9\. A lot of users have fixed this installation issue for Xbox Game Pass titles with the resolutions in this guide.

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
<li><a href="https://windows11.techidaily.com/rejuvenating-your-apathetic-windows-start-button-click/"><u>Rejuvenating Your Apathetic Windows Start Button Click</u></a></li>
<li><a href="https://windows11.techidaily.com/top-secure-password-vaults-elevating-windows-11-standards/"><u>Top Secure Password Vaults Elevating Windows 11 Standards</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-advanced-file-navigation-skills-steering-clear-of-ls/"><u>Unraveling Advanced File Navigation Skills: Steering Clear of LS</u></a></li>
<li><a href="https://windows11.techidaily.com/delaying-windows-11-shutdown-managing-ongoing-processes/"><u>Delaying Windows 11 Shutdown: Managing Ongoing Processes</u></a></li>
<li><a href="https://windows11.techidaily.com/easing-the-load-streamlining-windows-11-mails-email-display/"><u>Easing the Load: Streamlining Windows 11 Mail's Email Display</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essence-of-personalization-through-ai-at-ms-store/"><u>The Essence of Personalization Through AI at MS Store</u></a></li>
<li><a href="https://windows11.techidaily.com/image-integration-insights-securely-stashing-files-on-windows-11/"><u>Image Integration Insights: Securely Stashing Files on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/chronological-corrections-6-utilities-to-edit-file-timestamps/"><u>Chronological Corrections: 6 Utilities to Edit File Timestamps</u></a></li>
<li><a href="https://windows11.techidaily.com/enabling-hidden-programs-on-windows-pc/"><u>Enabling Hidden Programs on Windows PC</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-xiaomi-redmi-note-12-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some Pro Tips for Pokemon Go PvP Battles On Xiaomi Redmi Note 12 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-ideal-mac-tools-to-record-your-workscreen/"><u>In 2024, Ideal Mac Tools to Record Your Workscreen</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/apple-iphone-14-mirror-to-pc-top-apps-you-must-know-drfone-by-drfone-ios/"><u>Apple iPhone 14 Mirror to PC? Top Apps You Must Know | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/mastering-the-art-of-creating-top-quality-edu-videos-for-learning-platforms-for-2024/"><u>Mastering the Art of Creating Top-Quality Edu-Videos for Learning Platforms for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/8-ultimate-fixes-for-google-play-your-oppo-a59-5g-isnt-compatible-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Ultimate Fixes for Google Play Your Oppo A59 5G Isnt Compatible | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-decoding-authenticity-in-your-digital-instagram-family/"><u>[New] Decoding Authenticity in Your Digital Instagram Family</u></a></li>
<li><a href="https://animation-videos.techidaily.com/10-most-memorable-japanese-cat-cartoons-for-2024/"><u>10 Most Memorable Japanese Cat Cartoons for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/spotify-keeps-crashing-a-complete-list-of-fixes-you-can-use-on-xiaomi-redmi-k70-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Spotify Keeps Crashing A Complete List of Fixes You Can Use on Xiaomi Redmi K70 | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-pinnacle-graphic-designer-tools-for-free-discord-logos/"><u>2024 Approved  Pinnacle Graphic Designer Tools for FREE Discord Logos</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/getting-started-with-m4r-conversion-top-things-to-keep-in-mind-for-2024/"><u>Getting Started with M4R Conversion Top Things to Keep in Mind for 2024</u></a></li>
</ul></div>
