---
title: Adjusting Low-Power Options for Better Battery Life
date: 2024-08-15T15:15:14.840Z
updated: 2024-08-16T15:15:14.840Z
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

## 1\. How to Enable or Disable Battery Saver Mode Using Quick Settings

 The [Quick Settings panel in Windows](https://www.makeuseof.com/use-quick-settings-on-windows-11/) provides access to frequently used features such as Wi-Fi, Bluetooth, Airplane Mode, and others. You can also access this panel to turn the battery saver mode on or off quickly.

 Simply press**Win + A** to open the Quick Settings panel, and then click the**Battery saver** icon to enable or disable it.

![Enable or Disable Battery Saver in via Quick Settings Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-or-disable-battery-saver-in-via-quick-settings-panel.jpg)

 In case the Battery saver icon is missing, you can add it manually. Click the**pencil** icon at the bottom, and then select**Add > Battery saver** .

![Add Battery Saver Button to Quick Settings Panel in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/add-battery-saver-button-to-quick-settings-panel-in-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. How to Enable or Disable Battery Saver Mode Using the Settings App

 Another way to turn the battery saver mode on or off in Windows is via the Settings app. To do so, use these steps:

1. Right-click on the**Start icon** and select**Settings** from the list.
2. In the**System** tab, click on**Power & battery** .
3. Under**Battery** , click on**Battery saver** to expand it.
4. Click the**Turn on now** button to enable battery saver mode.  
![Enable or Disable Battery Saver in via the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-or-disable-battery-saver-in-via-the-settings-app.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->

 If the battery saver mode is on, you will see the**Turn off now** button instead. Further, plugging your laptop into a power outlet will also disable the battery saver mode.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
## 3\. How to Configure the Battery Saver Mode to Turn On Automatically on Windows

 Don’t want to enable the battery saver mode manually all the time? No problem. You can configure Windows to activate battery saver mode automatically whenever the battery level drops below a specific percentage. To do so, you can use the Windows Settings app. Here are the steps you can follow.

1. Press**Win + I** to open the Settings app.
2. Navigate to**System > Power & battery** .
3. Click on**Battery saver** to expand it.
4. Click the drop-down menu next to**Turn battery saver on automatically at** and select your preferred battery level.  
![Configure the Battery Saver Mode to Turn On Automatically in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/configure-the-battery-saver-mode-to-turn-on-automatically-in-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->

 You can also prevent Windows from enabling battery saver mode on its own by selecting**Never** . Alternatively, if you want the battery saver mode to be enabled at all times, choose**Always** instead.

 Although the Settings app is the most commonly used method for configuring the battery saver mode in Windows, it's not the only option available. You can also use a command-line tool like Command Prompt or Windows PowerShell to configure the battery saver mode to turn on automatically. Here are the steps for the same.

1. Use one of the [many ways to open Command Prompt or PowerShell](https://www.makeuseof.com/windows-open-command-prompt-powershell/) on your PC.
2. Type the following command in the console and press**Enter** .  
`powercfg /setdcvalueindex scheme_current sub_energysaver esbattthreshold <BatteryPercentage>`

 Replace**<BatteryPercentage>** in the above command with the percentage below which you want the battery saver mode to kick in automatically. Unlike the Settings app, you can specify a custom battery level percentage between 0 and 100 using the command line method.

![Configure the Battery Saver Mode to Turn On Automatically Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/configure-the-battery-saver-mode-to-turn-on-automatically-using-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->

 While PowerShell and Windows Terminal may look similar, they act very differently. Check our detailed guide to learn [the differences between PowerShell and Windows Terminal](https://www.makeuseof.com/windows-terminal-vs-powershell/) .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
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






