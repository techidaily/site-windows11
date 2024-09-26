---
title: Managing Antivirus Software’s RAM Consumption
date: 2024-08-27T16:05:06.836Z
updated: 2024-08-28T16:05:06.836Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Managing Antivirus Software’s RAM Consumption
excerpt: This Article Describes Managing Antivirus Software’s RAM Consumption
keywords: Manage AV RAM Usage,Optimize Antivirus Memory,Reduce AV RAM Load,Lower AV RAM Costs,Control Antivirus RAM,Efficient Antivirus RAM,Minimize AV Software RAM
thumbnail: https://thmb.techidaily.com/7618ed5212ad2fa17c4d0cff006f1dcb4d7c52766a583e2029f0351c0b405229.jpg
---

## Managing Antivirus Software’s RAM Consumption

 If you’ve kept a close eye on the Task Manager, then you may have noticed the Antimalware Service Executable doing its job. It is a crucial process of Windows Security (previously "Microsoft Defender") and helps keep your system safe from malware. It is pretty common to disable the Antimalware Service Executable because it consumes a large chunk of the system resources.

 On older PCs with limited system resources, the Antimalware Service Executable can severely impact the performance of your system. Read on as we discuss the importance of this service and how you can disable it.

## What Is the Antimalware Service Executable?

 You’re probably familiar with Windows Security (previously Microsoft Defender). Windows Security is a reliable antivirus that comes pre-installed on Windows 10 and 11\. The Antimalware Service Executable (you may find it listed as**MsMpEng.exe** in the**Task Manager**) is a core part of Windows Security.

 The service helps ensure your PC stays protected against any virus, worms, and other malware by continually scanning files and programs on your PC in the background. If the Antimalware Service Executable finds a malicious file or program, it will immediately delete or quarantine the affected files.

## Should You Disable the Antimalware Service Executable?

 Considering how integral the Antimalware Service Executable is to protect your PC, you must be wondering why you should even consider disabling it.

 If you do not have a third-party antivirus installed on your system, then Windows Security is your sole protection against potentially harmful malware. If your PC is left without any third-party antivirus programs installed, the Antimalware Service Executable automatically enables itself and begins safeguarding your PC as part of Windows Security.

 Ideally, you should not turn off the Antimalware Service Executable process. But if you have a reliable third-party antivirus installed, and the Antimalware Service Executable is still consuming a large chunk of your RAM or CPU, then it might make sense to disable it.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
## How to Disable the Antimalware Service Executable

 There are a few different ways you can disable the Antimalware Service Executable depending on the circumstances of your system’s performance.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Method 1: Disable Real-time Protection

 Suppose you find the Antimalware Service Executable process consuming a lot of system resources in certain instances; in that case, you can temporarily disable[real-time](https://www.makeuseof.com/real-time-protection/) malware protection through Windows Security:

1. Head to the**Start** menu, search for**Windows Security** and select the Best match.
2. Navigate to**Virus & threat protection** from the sidebar.
3. Look for**Virus & threat protection settings** , and then click on**Manage settings** option underneath.  
![real time protection windows security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/real-time-protection.jpg)
4. Disable the**Real-time protection** toggle button by bringing it to the**Off** position.
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->

 Real-time protection will be turned back on automatically by Windows Security.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
### Method 2: Turn Off Antimalware Service Executable Through Windows Security in the Registry Editor

 For users looking for a more permanent solution to disabling the Antimalware Service Executable, you will have to[disable Windows Security](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) from the Registry Editor.

 If you do not have a third-party antivirus installed, disabling Windows Security will leave your system at risk of malicious malware that can damage it.

To disable Antimalware Service Executable from the Registry Editor:

1. Search for**Registry Editor** from the**Start** menu, and launch it.
2. Navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows Defender** from the sidebar.
3. Right-click on the**Windows Defender** folder and select**New > DWORD (32-bit) Value** .  
![regedit windows defender](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/regedit-windows-defender.jpg)
4. Enter**DisableAntiSpyware** in the**Value name** field and**1** in the**Value data** field.
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
5. Press**OK** to save your changes and restart your system for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Should You Rely on Windows Security for Windows 10 and 11?

 Many users opt for a dedicated third-party antivirus on Windows 10 or 11, but Windows Security has made significant improvements in the past few years. Not only is Windows Security a complete antivirus package, but it's also free and comes pre-installed on Windows.

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


