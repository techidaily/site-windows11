---
title: Troubleshooting Error 0X80072EFD on Windows Devices
date: 2024-08-22T21:40:49.641Z
updated: 2024-08-23T21:40:49.641Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Error 0X80072EFD on Windows Devices
excerpt: This Article Describes Troubleshooting Error 0X80072EFD on Windows Devices
keywords: Windows Error 0X80072EFD Fix,Resolve 0X80072EFD Windows Error,Troubleshoot 0X80072EFD Error,Fixing 0X80072EFD on PCs/Laptops,Overcoming 0X80072EFD Issue Windows,Remedy 0X80072EFD in Windows Devices,Solving 0X80072EFD Error Windows OS
thumbnail: https://thmb.techidaily.com/f0ebe7bbeaa83391f6bb15edc8e752caf5cabced73b47f7e6c93255938daeeee.jpg
---

## Troubleshooting Error 0X80072EFD on Windows Devices

 Users have reported a 0x80072EFD Microsoft Store error on support forums that can arise in Windows 11 or 10\. Those users see a "server stumbled" or "check your internet connection" message with a 0x80072EFD error code inside MS Store after launching that app. When this error pops up, users can't utilize the Microsoft Store.

 The 0x80072EFD error is often a connection-related one. However, it occurs even when users can surf the web in their browsers. If you need to fix the 0x80072EFD error, try fixing it with these potential resolutions.

## 1\. Run the Windows Store App Troubleshooter

 Running the Windows Store App troubleshooter is a straightforward potential resolution for the 0x80072EFD error to start with. That troubleshooting tool might detect issues and give you a fix. You can open and run the Windows Store App troubleshooter like this:

1. Press**Start** and click the menu shortcut to open Settings.
2. Select the**Troubleshoot** section of Settings.
3. Click on**Other trouble-shooters** to look through the troubleshooting tools.
4. Select Windows Store Apps'**Run** option to bring up that troubleshooting tool.  
![The troubleshooter list in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/troubleshooter-list-in-windows-11.jpg)
5. Go through and apply any suggestions the troubleshooter offers.  
![The Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-store-apps.jpg)

**Internet Connections** is another troubleshooter that may be useful for fixing the Microsoft Store's 0x80072EFD error. So, consider running that troubleshooter if the Windows Store Apps option doesn't help.

 Note that the troubleshooting tools are accessible in the**Update & Security** category in the Settings app if you use Windows 10\. Click the**Troubleshoot** tab and**Additional troubleshooters** option to access them from there. Then press the**Run this troubleshooter** buttons for Windows Store Apps or Internet Connections.

## 2\. Refresh the SoftwareDistribution Folder

 SoftwareDistribution is a folder for temporarily storing Windows update files. Sometimes refreshing that folder by renaming it can resolve error**0x80072EFD** . Rename the SoftwareDistribution folder like this:

1. Hold down the**Windows** key and press**S** to access a search utility.
2. Type in**cmd** to find a Command Prompt app.
3. Open Command Prompt with elevated permissions by clicking its**Run as administrator** option in the search tool.
4. Turn off some services by executing these separate commands:  
`net stop wuauserv  
net stop cryptSvc  
net stop bits  
net stop msiserver`
5. To rename SoftwareDistribution, type in the following and hit**Enter** :  
`ren C:\Windows\SoftwareDistribution SoftwareDistribution.old`  
![The rename SoftwareDistribution.old folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/rename-softwaredistribution-old-folder.jpg)
6. Also, rename a catroot2 directory with this command:  
`ren C:\Windows\System32\catroot2 catroot2.old`  
![The rename catroot2 command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/rename-catroot2-command.jpg)
7. Restart the turned-off services by inputting and executing the following commands:  
`net start wuaserv  
net start cryptSvcc  
net start bits  
net start msiserver`
8. Then bring up your Start menu to select**Restart** .

## 3\. Reset the Microsoft Store's Cache

 Microsoft store has a cache in which data accumulates. Resetting or clearing that cache's data is a reliable solution to various Microsoft Store issues. So, we recommend users try doing that when troubleshooting the 0x80072EFD error. You can clear that cache in Settings, as covered in our[guide for resetting apps](https://www.makeuseof.com/windows-reset-app/) in Windows 11 and Windows 10.

![The Reset button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-button.jpg)

## 4\. Turn Off Proxy Server

 Some users who've needed to fix error 0x80072EFD have confirmed they resolved that issue by turning off the proxy server setting. That's because a proxy server generated a Microsoft Store connection issue on those users' PCs. You can check if a proxy server is enabled on your PC and disable it in the following steps:

1. Start the Run dialogue by pressing**Win** +**R** .
2. Type**inetcpl.cpl** inside Run's command box and click**OK** to open Internet Options.
3. Select**Connections** \>**LAN settings** to reach a**Use a proxy server** setting.  
![The LAN settings button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/advanced-tab.jpg)
4. Uncheck the checkbox for**Use a proxy server** if it's selected.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
5. Click the**Automatically detect settings** option to select it.  
![The Use a proxy server for your LAN checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/use-a-proxy-server-option.jpg)
6. Select the Local Area Network window's**OK** option.
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Double-Check the Time Settings in Windows

 An incorrect region time on your PC is another potential cause for error 0x80072EFD. Users have confirmed they've fixed error 0x80072EF by adjusting time settings on their PCs. The Microsoft Store's time tracking needs to sync with the PC's set regional time. So, have a look through your time settings as follows:

1. [Open up Settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/) , and click that app's**Time & language** tab.
2. Click**Date & time** to view those settings.  
![The Date & time navigation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/date-time-tab.jpg)
3. Select to turn off the**Set time zone** option there.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
4. Make sure the correct time zone for your location is selected in the**Time Zone** drop-down menu.  
![The Set the time zone automatically option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/set-the-time-automatically-option.jpg)
5. Then press the**Sync now** button.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Sync now button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sync-now-button.jpg)

<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Alternatively, you can manually set the time by disabling the Set the time automatically option. Press the**Change** button for the**Set the date and time manually** option. Check the date and exact time for your location via online sources, and then enter it inside the**Change date & time** box.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
## 6\. Enable TLS Protocols

 TLS is an encryption protocol that ensures your data privacy online. It's widely used and is essential for security when your computer communicates with internet servers.

1. Open Internet Options as specified in the first two steps for the fourth resolution.
2. Then select**Advanced** inside the Internet Options window.
3. Scroll down to the**Security** section on the**Advanced** tab.
4. Select the**TLS 1.0** ,**1.1** ,**1.2** , and**1.3** checkboxes there.  
![The Advanced tab in Internet Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-advanced-tab.jpg)
5. Click**Apply** to set the protocol options.
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
6. Select**OK** to exit the Internet Options window.

## 7\. Reregister Microsoft Store

 You can't reinstall Microsoft Store like other apps. However, reregistering it with PowerShell is similar to reinstalling. If other potential solutions don't fix the 0x80072EFD error, reregistering MS Store is worth a try. This is how you can register that app:

1. Activate the**Type here to search** box with that tool's**Windows** +**S** hotkey.
2. Enter**PowerShell** within that tool's search box.
3. Launch Windows PowerShell with elevated permissions by clicking that search result's**Run as administrator** option.
4. Input this command for reregistering MS Store and hit**Return** to execute:  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reregister MS Store command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reregister-ms-store-command.jpg)
5. Wait until you're sure the command has finished.
6. Then exit PowerShell, and select the**Restart** option.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
## 8\. Reset Your Network

 Resetting network settings in Windows is another 0x80072EFD error fix that's worked for some users. Note that this measure will erase Wi-Fi and Ethernet connection details, so you'll need to re-establish your connection after applying it. You can apply this potential fix as covered in our[how-to reset networks in Windows 11](https://www.makeuseof.com/reset-network-settings-windows-11/) guide.

![The Reset now button for networks](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-now-network-option.jpg)

## Get Shopping in Microsoft Store Again

 The 0x80072EFD error isn't always easy to fix, and you may have to try applying quite a few potential resolutions to get it sorted. However, many Microsoft Store users have fixed the 0x80072EFD error with the solutions in this guide. So, maybe one of those potential fixes will also work on your PC.

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


