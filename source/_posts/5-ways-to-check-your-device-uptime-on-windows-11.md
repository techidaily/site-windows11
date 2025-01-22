---
title: 5 Ways to Check Your Device Uptime on Windows 11
date: 2025-01-15T16:25:44.253Z
updated: 2025-01-22T16:34:54.568Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 5 Ways to Check Your Device Uptime on Windows 11
excerpt: This Article Describes 5 Ways to Check Your Device Uptime on Windows 11
keywords: Win11 Uptime Check,Windows Uptime Test,DevUptime Monitoring,PC Up Time Verify,Device Availability Windows,OS Health Status,System Downtime Check
thumbnail: https://thmb.techidaily.com/3df80ed0f3ba1234db4e3fe9b6b618140f5c8ecbd00a02e86f21f161aa5eef49.jpg
---

## 5 Ways to Check Your Device Uptime on Windows 11

 Checking your computer's uptime is something you might want to do to monitor its performance. This information can also come in handy when troubleshooting your system or performing regular maintenance tasks.

 Your Windows 11 PC provides several options for checking the device's uptime. Let’s go over all of them one by one.

## 1\. How to Find System Uptime Using Task Manager

 Windows Task Manager is an advanced tool that provides useful information about your PC’s hardware and software. Here's how you can use it to find your computer’s uptime.

1. Press**Ctrl + Shift + Esc** on your keyboard or use one of the [many ways to access Task Manager](https://www.makeuseof.com/how-to-access-task-manager-on-windows-11/) .
2. In the**Performance** tab, click on**CPU** .
3. Check the system uptime under the**Up time** section.  
![Check System Uptime Using Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-task-manager.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Find System Uptime via the Settings App

 Another way to check your system's uptime is through the Windows Settings app. Here are the steps for the same.

1. Press**Win + I** to open the Settings app.
2. Select the**Network & internet** tab from the left sidebar.
3. Click on**Advanced network settings** .
4. Under the**Network adapters** section, click on the active network adapter and check the uptime mentioned next to**Duration** .  
![Check System Uptime Using Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-windows-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MHafwnWSEQk?si=rejNVNpJZH2SqNLy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Note that this method displays your network adapter’s uptime. So, the information displayed may not be accurate if you have reset your network connection after boot.

## 3\. How to Find System Uptime Using Control Panel

 If you prefer to do things the old-fashioned way, you can use the classic Control Panel to find your device’s uptime in Windows 11\. To do so, use the following steps:

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**control panel** in the box and select the first result that appears.
3. In the Control Panel window that appears, use the drop-down menu in the top right corner to change the view type to**Large icons** .
4. Click on**Network and Sharing Center** .
5. Click on**Change adapter settings** in the left pane.
6. Right-click on the active network adapter and select**Status** .
7. Under the**General** tab, you’ll find the uptime next to**Duration** .  
![Check System Uptime Using Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-control-panel.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5FWCFI3f_cs?si=Kt2Onr_E4c616tbH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qv4Qm7kpeMs?si=9fv5SOS5a2DvixTK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. How to Check System Uptime With Command Prompt

 If you're an advanced Windows user, you can also use Command Prompt to check your computer’s uptime. Here’s how:

1. Right-click on the Start icon or press**Win + X** to open the Power User menu.
2. Select**Terminal** from the list.
3. Type the following command in the console and press**Enter** .  
`systeminfo | find "System Boot Time"`  
![Check System Uptime Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you run the above command, Command Prompt should display the time when your computer started operating. You can easily calculate the system uptime by subtracting the**System Boot Time** from the current time.

## 5\. How to Check System Uptime With PowerShell

 PowerShell is another command-line tool available on Windows. If you prefer using that, follow these steps to find your device’s uptime.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**Windows PowerShell** and press**Enter** .
3. Paste the following command in the PowerShell window and press**Enter** .  
`(get-date) - (gcim Win32_OperatingSystem).LastBootUpTime`  
![Check System Uptime Using Windows PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-windows-powershell.jpg)

 PowerShell should display the number of days, hours, minutes, seconds, and milliseconds since the device was turned on.

 Like using PowerShell on Windows? Why not familiarize yourself with these [best PowerShell commands on Windows](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) ?

## Checking Your Device Uptime on Windows 11

 As we just saw, finding your Windows 11 PC’s uptime is fairly simple. You can use any of the methods listed above to find that information.

 The total uptime of your computer may not provide you with accurate information about how much time you spend in front of it. For that, you’ll need to check Power & battery usage in the Windows Settings app.

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
<li><a href="https://article-knowledge.techidaily.com/updated-2024-approved-comparing-broadcast-tools-go-with-wirecast-or-obs/"><u>[Updated] 2024 Approved Comparing Broadcast Tools Go With Wirecast or OBS?</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-curating-your-ringtone-with-holy-hymns-step-by-point/"><u>[Updated] Curating Your Ringtone with Holy Hymns Step-By Point</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-free-and-fast-guide-to-detecting-fraudulent-accounts-among-instragrammers/"><u>[Updated] Free & Fast Guide to Detecting Fraudulent Accounts Among Instragrammers</u></a></li>
<li><a href="https://extra-information.techidaily.com/elevate-your-creations-the-7-most-innovative-nft-generators/"><u>Elevate Your Creations - The 7 Most Innovative NFT Generators</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-solutions-to-find-your-xiaomi-redmi-note-12r-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Solutions to Find Your Xiaomi Redmi Note 12R Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-a-perfect-guide-to-remove-or-disable-google-smart-lock-on-infinix-zero-30-5g-by-drfone-android/"><u>In 2024, A Perfect Guide To Remove or Disable Google Smart Lock On Infinix Zero 30 5G</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-off-game-lists-in-win11/"><u>Mastering Off Game Lists in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/minimizing-resource-waste-during-device-integration-on-windows/"><u>Minimizing Resource Waste During Device Integration on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/selecting-a-window-for-your-needs-the-win11-homepro-showdown/"><u>Selecting a Window for Your Needs: The Win11 Home/Pro Showdown</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/step-up-strategy-from-windows-10-home-to-pro-edition/"><u>Step-Up Strategy: From Windows 10 Home to Pro Edition</u></a></li>
<li><a href="https://android-transfer.techidaily.com/tips-of-transferring-messages-from-infinix-smart-8-hd-to-iphone-1415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Tips of Transferring Messages from Infinix Smart 8 HD to iPhone 14/15 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-your-windows-11-pc-into-a-portable-wireless-router/"><u>Turn Your Windows 11 PC Into a Portable Wireless Router</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-tutorial-for-implementing-the-black-lightning-extension-in-kodi-versions-19-and-18/"><u>Ultimate Tutorial for Implementing the Black Lightning Extension in Kodi Versions 19 & 18</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-efficiency-9-gains-from-the-newest-outlook-update/"><u>Unlocking Efficiency: 9 Gains From the Newest Outlook Update</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-power-of-outlook-preview-on-windows-11/"><u>Unlocking the Power of Outlook Preview on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-yourphoneexe-usefulness-on-modern-windows/"><u>Unlocking YourPhone.exe: Usefulness on Modern Windows?</u></a></li>
</ul></div>

