---
title: Clearing Up the Blocked App Notification Issue
date: 2024-08-08T06:00:35.230Z
updated: 2024-08-09T06:00:35.230Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Clearing Up the Blocked App Notification Issue
excerpt: This Article Describes Clearing Up the Blocked App Notification Issue
keywords: Fix Blocked App Alerts,Resolve App Notifications,Unblock App Notify Error,Clear App Block Notice,Stop App Blocking Message,Disable App Notification Halt,Remove Obstructed App Alert
thumbnail: https://thmb.techidaily.com/79c7e594da2bcc4e0b5a712ad425c9a3c9c769d4308cac3ac9d4efb24f911715.jpg
---

## Clearing Up the Blocked App Notification Issue

 While Windows is designed to keep your computer secure, sometimes it can be overly zealous in its protection and block an app you know is safe. If you’re seeing the “This app has been blocked for your protection” error on Windows, your system has restricted the application from running for security reasons. This article clarifies the reasons behind the problem and guides you toward resolving it.

<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Restart Your Computer

 When you experience the “This app has been blocked for your protection” error, the first step is to restart your computer. A simple reboot can often do the trick and allow you run a previously blocked application.

 If you don’t experience the error after rebooting, then it is likely a temporary glitch on Windows.

## 2\. Scan for Malicious Programs

 If restarting your computer doesn’t work, the next step is to run a full antivirus scan on your system. Chances are that the application is blocked due to a virus, malware or another malicious program.

 To be sure it's not the case, check whether a file is infected with a virus. If you find one, [scan your computer for viruses](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) and remove them.

 If you prefer command line tools, you can [scan and remove malicious components using Windows PowerShell](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/). You should also use a [reputable anti-spyware program](https://www.makeuseof.com/windows-11-antivirus-apps/) to check for malicious programs that could be causing the error.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Run the Program as an Administrator

 Some programs require administrator privileges to function properly. If you try to launch them without elevated access, Windows will block their execution and display the error message. In such a case, you can right-click on the app’s shortcut or the executable file and select **Run as administrator**.

 If it runs successfully, you can adjust the app properties to [always run as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/). Don't forget to save the changes.

## 4\. Disable the SmartScreen Filter

 SmartScreen is a security feature that protects your computer from unknown and potentially malicious applications. If it’s enabled, SmartScreen may block an application from running. To disable the feature, follow these steps.

1. Open the **Start** menu and search for _Windows Security_.
2. Click on **Windows Security** in the search results.
3. In the Windows Security app, select **App & browser control**.
4. On the right side of the window, click **Reputation-based protection settings**.  
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
![Disable the SmartScreen Filter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-the-smartscreen-filter.jpg)
5. Toggle off **Potentially unwanted app blocking** and **SmartScreen for Microsoft Store apps**.

 This will stop the system from blocking apps, but you should be careful with any programs you download. Once you do it, close the Windows Security app and try running the application again.

## 5\. Modify the Group Policy Settings

 The group policy editor allows you to adjust security settings on Windows and control which applications are blocked. If the other steps didn’t work, you can try to modify the group policy settings and unblock the application that triggered the error. Here's how to do it:

1. Press **Win + X** on your keyboard and select **Run** from the menu list.
2. Type **gpedit.msc** and press Enter to open the Local Group Policy Editor.  
<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![User Account Control Run all administrators in Admin Approval Mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/user-account-control-run-all-administrators-in-admin-approval-mode.jpg)
3. Once you're in the Local Group Policy Editor window, navigate to the following:  
`Local Computer Policy > Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options.`
4. From the list of settings, double-click on **User Account Control: Run all administrators in Admin Approval Mode** and set it to **Disabled**.
5. After making the changes, click **Apply > OK** and restart your computer to apply it.

 Keep in mind that modifying group policy settings can leave your computer vulnerable to malicious applications. Therefore, you should only do it as a last resort and revert the change as soon as you’re done.

## 6\. Tweak the Registry Editor

 If you're running Windows Home edition, you can tweak the Registry Editor to adjust the User Account Control settings and unblock the application. Here's what you need to do:

1. [Open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** and press Enter to open the Registry Editor window.
3. If UAC prompts you for permission, click **Yes**.
4. Navigate to the following key location.  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System`
5. In the right pane, double-click on **EnableLUA** and set its value to **0** (zero).  
<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Disable the EnableLUA key in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-the-enablelua-key-in-registry-editor.jpg)
6. Click **OK** to save the changes.

 After making the changes, close the Registry Editor and restart your computer.

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Reset Windows Update Components

 If the issue persists, you can reset the Windows Update components, which means restarting certain services that manage the update process and enable you to launch the application.

 To reset Windows Update components, do the following:

1. Click on Start and search for **Notepad**.
2. Right-click on the Notepad icon and select **Run as administrator**.
3. Copy and paste the following code into Notepad:  
`<code>net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc  
Del "%ALLUSERSPROFILE%\Application Data\Microsoft\Network\Downloader\*.*"  
rmdir %systemroot%\SoftwareDistribution /S /Q  
rmdir %systemroot%  
system32\catroot2 /S /Q  
sc.exe sdset bits D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
sc.exe sdset wuauserv D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
cd /d %windir%  
system32  
regsvr32.exe /s atl.dll  
regsvr32.exe /s urlmon.dll  
regsvr32.exe /s mshtml.dll  
regsvr32.exe /s shdocvw.dll  
regsvr32.exe /s browseui.dll  
regsvr32.exe /s jscript.dll  
regsvr32.exe /s vbscript.dll  
regsvr32.exe /s scrrun.dll  
regsvr32.exe /s msxml.dll  
regsvr32.exe /s msxml3.dll  
regsvr32.exe /s msxml6.dll  
regsvr32.exe /s actxprxy.dll  
regsvr32.exe /s softpub.dll  
regsvr32.exe /s wintrust.dll  
regsvr32.exe /s dssenh.dll  
regsvr32.exe /s rsaenh.dll  
regsvr32.exe /s gpkcsp.dll  
regsvr32.exe /s sccbase.dll  
regsvr32.exe /s slbcsp.dll  
regsvr32.exe /s cryptdlg.dll  
regsvr32.exe /s oleaut32.dll  
regsvr32.exe /s ole32.dll  
regsvr32.exe /s shell32.dll  
regsvr32.exe /s initpki.dll  
regsvr32.exe /s wuapi.dll  
regsvr32.exe /s wuaueng.dll  
regsvr32.exe /s wuaueng1.dll  
regsvr32.exe /s wucltui.dll  
regsvr32.exe /s wups.dll  
regsvr32.exe /s wups2.dll  
regsvr32.exe /s wuweb.dll  
regsvr32.exe /s qmgr.dll  
regsvr32.exe /s qmgrprxy.dll  
regsvr32.exe /s wucltux.dll  
regsvr32.exe /s muweb.dll  
regsvr32.exe /s wuwebv.dll  
netsh winsock reset  
netsh winsock reset proxy  
net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`
4. Now click **File** in the top left corner.
5. Then select **Save as** from the options list.
6. In the Save as window, name your script **Reset.bat** and set the Save as type to **All Files**.
7. Select **Desktop** from the left menu and click **Save**.
8. Double-click on the **Reset.bat** file to run it as an administrator.
9. If the UAC window pops up on the screen, click **Yes** to continue.

 Wait for the process to finish and restart your computer. After the reboot, try running the blocked app again. It should now work without issues.

## Get Access to Your Apps and Files on Windows

 Windows is known for its tight security which prevents malicious applications from launching and infecting your PC. However, sometimes even legitimate programs are blocked by the operating system and leave an error message saying “This app has been blocked for your protection.”

 There are several reasons why this error occurs. It includes outdated security software, the firewall interfering with the program, or the application not trusted by Windows. Read this guide to learn more about this error.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

