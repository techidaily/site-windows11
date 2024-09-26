---
title: 5 Ways to Check Your Device Uptime on Windows 11
date: 2024-08-15T15:19:15.118Z
updated: 2024-08-16T15:19:15.118Z
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
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. How to Find System Uptime via the Settings App

 Another way to check your system's uptime is through the Windows Settings app. Here are the steps for the same.

1. Press**Win + I** to open the Settings app.
2. Select the**Network & internet** tab from the left sidebar.
3. Click on**Advanced network settings** .
4. Under the**Network adapters** section, click on the active network adapter and check the uptime mentioned next to**Duration** .  
![Check System Uptime Using Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-windows-settings-app.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
## 4\. How to Check System Uptime With Command Prompt

 If you're an advanced Windows user, you can also use Command Prompt to check your computer’s uptime. Here’s how:

1. Right-click on the Start icon or press**Win + X** to open the Power User menu.
2. Select**Terminal** from the list.
3. Type the following command in the console and press**Enter** .  
`systeminfo | find "System Boot Time"`  
![Check System Uptime Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-system-uptime-using-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->
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






