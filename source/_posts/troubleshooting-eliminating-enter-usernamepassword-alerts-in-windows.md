---
title: "Troubleshooting: Eliminating 'Enter Username/Password' Alerts in Windows"
date: 2024-08-15T15:45:08.489Z
updated: 2024-08-16T15:45:08.489Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Troubleshooting: Eliminating 'Enter Username/Password' Alerts in Windows"
excerpt: "This Article Describes Troubleshooting: Eliminating 'Enter Username/Password' Alerts in Windows"
keywords: Fix Login Prompt on PC,Disable User Credential Alert,Remove Password Entry Screen,Stop WinLogin Popup,End Username/Password Window,Eliminate Authenticate Warning,Bypass Windows Login Screen
thumbnail: https://thmb.techidaily.com/b4ed3f08ab6e820bb58ff66c5f5e67696c65d753e22482d093bffe3ae2ca67e1.png
---

## Troubleshooting: Eliminating 'Enter Username/Password' Alerts in Windows

 The network credentials on your PC are important because they prevent others from using your computer across the network. While this feature is essential to protect your important files and improve the overall security of your system, it can sometimes cause issues as well.

 A common problem is when the network credential manager keeps displaying the "Enter network credentials" dialog, even when you enter the correct credentials. In this guide, we will walk you through some troubleshooting methods you can try to fix this issue for good.

## 1\. Modify the Advanced Sharing Settings

 An incorrectly set Advanced Sharing setting is one of the most common causes of this error. Ideally, your PC should be allowed to manage homegroup connections. You can also use the Advanced Sharing settings page to disable password-protected sharing, which will allow you to share files without needing to log in.

 Here is how you can configure the Advanced Sharing settings correctly:

1. Locate the network icon on your taskbar and right-click on it.
2. Choose **Network and Internet settings** from the context menu.  
![Network and Internet settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/network-and-internet-settings.jpg)
3. In the following window, select **Network and Sharing Center**.
4. Choose **Change advanced sharing settings** option in the left pane.
5. Now, enable the **Allow Windows to manage homegroup connections (recommended)** option under Homegroup connections.
6. Click **Save changes** (you will need administrative access for this).
7. Now, expand the **All Networks** section and enable the **Turn off password protected sharing** option.  
![Turn off password sharing option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/turn-off-pasword-sharing.jpg)
8. Hit the **Save changes** button to complete the process.

 After you've transferred the files, re-enable password-protected sharing so that others don't get easy access to your PC.

## 2\. Use Your Microsoft Account Credentials or the Computer's Name

 You can also try logging onto the target PC using the Microsoft account credentials instead of the local username and password.

 Alternatively, you can also try using the name of the computer you are using alongside your username in the text field associated with the Username. Do not enter a space, bar, or any other symbol between the names.

 If the problem is associated with the credentials, one of these two methods is likely to help you get rid of it for good.

<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Manually Add the Credentials of the Target Computer to the Credential Manager

 Another way to fix the issue is by manually adding the credentials of the targeted computer in the Credential Manager and seeing if that makes a difference.

 Here is how you can do that:

1. Type "Credential Manager" into Windows Search and click **Open**.
2. Select **Windows Credential** and click on **Add a Windows Credential**.  
![Windows credentials](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/windows-credentials-1.jpg)
3. Now, add the username, computer name, and password of the computer you are trying to access. Check if you can now share files with the other device successfully.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Create a New User Account on Both Devices

 There are times when user accounts become corrupt and stop you from performing certain actions. If this has happened, either on your PC or the target computer, it can interrupt the file-sharing process.

 To fix this problem, first, try [switching to a different user account](https://www.makeuseof.com/windows-11-switch-user-accounts/) on your own computer and see if that works. If this strategy fails, then we recommend [creating a new user account](https://www.makeuseof.com/windows-11-create-local-user-account/) on both devices with the same username and password. Make sure that both accounts have administrative privileges. While you are at it, we also suggest temporarily disabling any third-party antivirus program that you might be using, as it can sometimes block network access.

 If the root of your issue was a corrupt user account, this should be enough to fix the issue.

## 5\. Restart the Credential Manager Service

 The issue might also be with the Credential Manager service itself instead of the targeted computer or the network settings of your device. In this method, we will first enable the Credential Manager service if the service is disabled.

 If it is working already, then we will proceed with restarting the service and see if that does the trick.

 Here is what you need to do:

1. Press **Win** \+ **R** to open Run.
2. Type services.msc in the Run and click **Enter**.
3. In the following window, look for the Credential Manager service and right-click on it.
4. Choose **Properties** from the context menu.
5. If the service is disabled, click on the **Start button** to enable it.
6. In case it is working already, click on the **Stop button**, wait for a few seconds, and then hit the **Start button**.
7. ![Credential Manager properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/credential-manager-properties.jpg)  
 Make sure that the Startup type is set to **Automatic**.  
![Credential Manager service properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/credential-manager-service.jpg)
8. Click **Apply** \> **OK** to save the changes.

 Now try connecting to the targeted computer and see if you can do so without any problems.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
## 6\. Make Changes to the Local Security Policy

 Several users also managed to fix the problem by modifying the settings of the "Accounts: Limit local account use of blank passwords to console logon only" policy. Here is how you can give it a try too:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "secpol.msc" in Run and click **Enter**.
3. In the following window, navigate to the following location:  
Local Policies > Security Options > Accounts: Limit local account use of blank passwords to console logon only
4. Choose **Disabled** and click **Apply** \> **OK** to save the changes.  
![Make changes to the Local Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-security-policy.jpg)
5. Restart your computer and check if the issue is resolved.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Try Using Safe Mode With Networking

 If the credentials you are entering and all the network configurations on the system are correct, something might have gone wrong on a system level.

 In this case, you can boot into Safe Mode to determine the cause of the issue. Safe Mode starts Windows with only the basic set of drivers and apps — the ones that are essential for the operating system to function.

 There are several types of Safe Mode including Minimal, Alternate Shells, Active Directory Repair, and Network. In this method, we will be booting Windows into Safe Mode with Networking. This mode launches Windows with the drivers and programs required to connect the system to the internet or other devices over the network.

 If the error at hand does not appear in Safe Mode, then there is a chance that malware or other software issues are causing the problem.

 Here is what you need to do:

1. Head over to the Start menu and click on the **Power button**.
2. Choose **Restart** while holding the **Shift key**.
3. Wait for the Windows to boot into the recovery mode and then choose **Troubleshoot** \> **Advanced Options**.
4. Navigate to **Startup Settings** \> **Restart**.
5. In the following window, press the **F5 key** on your keyboard to boot into Safe Mode with Networking.  
![Pick safe mode with Networking option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/Tweak-Startup-Settings-1.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
6. Once you are logged into Safe Mode, try connecting to the device you were previously trying to connect to. If the error does not appear in Safe Mode, then you might want to report this issue to Microsoft’s official support team and wait for a fix from their side.

 In case you cannot access this Windows state using the steps outlined above, you can try [other ways of booting into Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/).

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Share Data Over Network Without Issues

 Windows has made it simpler to share your files and other data across networks, but there are times when you run into unexpected errors. Hopefully, one of the methods mentioned above did the trick for you in fixing the issue under consideration.

 A common problem is when the network credential manager keeps displaying the "Enter network credentials" dialog, even when you enter the correct credentials. In this guide, we will walk you through some troubleshooting methods you can try to fix this issue for good.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>



