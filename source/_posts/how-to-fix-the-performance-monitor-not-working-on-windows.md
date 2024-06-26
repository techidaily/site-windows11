---
title: How to Fix the Performance Monitor Not Working on Windows
date: 2024-06-21 23:28:32
updated: 2024-06-24 10:32:25
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the Performance Monitor Not Working on Windows
excerpt: This Article Describes How to Fix the Performance Monitor Not Working on Windows
keywords: Windows PM Issue Troubleshoot,Performance Monitor Error Resolve,PM Fix Guide Windows PC,Stop PM Not Functioning Windows,Solve Windows Performance Tool Fail,Correct Windows PM Malfunction,Fix Windows Monitor Slowness
thumbnail: https://thmb.techidaily.com/c6ed4dd6078fc00a4ccdd98c0ceccdb558ca50f259a821b95bf9be5b46566a3f.jpg
---

## How to Fix the Performance Monitor Not Working on Windows

 Performance Monitor is a system monitoring tool on Windows that you can use to view real-time statistics about the applications you are running. But sometimes this tool fails to work correctly. If you're facing such a problem on your computer, here are a few fixes you can try to solve it.

## 1\. Reboot your Computer

 Whether you're experiencing performance issues such as slow startup times, or if Performance Monitor isn't working on your system, a simple reboot might do the trick.

 Rebooting Windows clears out any conflicting programs or services that may be causing PerfMon to not work properly. It removes any unnecessary data stored in memory that might be responsible for the issue.

To restart your computer, follow these steps:

1. Open the**Start** menu.
2. Click on the Power button, then select**Restart** .

 Once the computer has restarted, open Performance Monitor and check if the issue has been resolved.

## 2\. Restart the Performance Logs and Alerts service

 If rebooting your computer doesn't fix the problem, you can try restarting the Performance Logs and Alerts service. This service is responsible for monitoring system performance settings and generating alert messages when something is wrong.

To restart this service, follow these steps:

1. Press**Win + R** on your keyboard to open the Run command
2. Type**services.msc** in the dialog box and press**Enter** .
3. In the Services window, scroll down to**Performance Logs & Alerts** service.
4. Right-click on the service and select the**Restart** option.  
![Restart Performance service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/restart-performance-service.jpg)

 After you follow the above steps, check if Performance Monitor is working correctly.

## 3\. Run the System File Checker

 The System File Checker is a handy Windows tool that can scan for and fix corrupted system files. It is useful when the Performance Monitor isn't working due to a corrupt system file.

To run the System File Checker, follow these steps:

1. Click on the Start menu.
2. Type**cmd** in the search bar, then press**Ctrl + Shift + Enter** to open an elevated Command Prompt.
3. If UAC appears on the screen, click**Yes** to grant access. You can learn more about this handy tool with our[beginner's guide to the Windows Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) .  
![Run SFC Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-sfc-command.jpg)
4. In the Command Prompt, type the following command and press**Enter** :  
sfc /scannow
5. The scan will check for any corrupted system files and repair them.

 After the scan is complete, restart your computer and check if Performance Monitor is working properly.

## 4\. Check for a Windows Update

 In some cases, outdated versions of Windows can cause Performance Monitor problems. To ensure your system is running the latest version of Windows, follow these steps:

1. Press**Win + I** on your keyboard to open System Settings. We also have an in-depth tutorial on[accessing the Settings menu](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Click**Windows Update** in the left pane.  
![Check for Updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/check-for-updates.jpg)
3. Then click the**Check for updates** button.

 If any available updates are found, Windows will download and install them automatically. After the updates have been installed, restart your computer and check if Performance Monitor is now working correctly.

## 5\. Perform a System Restore

 In case you have run out of options, you may want to try a system restore. This way, your computer will be restored to the state it was in before the program stopped working.

To perform a system restore, follow these steps:

1. Press**Win + Q** on your keyboard.
2. Type**System Restore** in the search bar and click on**Create a restore point** .
3. In the System Properties window, click the**System Restore** button.  
![Run System Restore](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-system-restore.jpg)
4. Choose a restore point, then click**Next** .
5. Follow the on-screen instructions to perform a system restore.

 Upon completion of the restoration process, make sure Performance Monitor is working properly.

## Get Hassle Free Performance and Health Monitoring

 Like any other program, Performance Monitor can have glitches and other issues that prevent it from working correctly. The steps in this article will help you fix these issues and get Performance Monitor up and running again.


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
