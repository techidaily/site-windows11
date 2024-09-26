---
title: Troubleshooting the Stalled Windows System Insight
date: 2024-08-15T15:34:44.231Z
updated: 2024-08-16T15:34:44.231Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting the Stalled Windows System Insight
excerpt: This Article Describes Troubleshooting the Stalled Windows System Insight
keywords: Insight Troubleshoot Guide,Windows System Freeze Fix,Insight Error Analysis,Fixing Insight Logs,Insight Performance Halt,Resolving Insight Crashes,Insight Diagnostic Tools
thumbnail: https://thmb.techidaily.com/527ec40dbef906cadfd5828e1a10f887ec75fd463af4e51940397e62459c5f66.jpg
---

## Troubleshooting the Stalled Windows System Insight

 Performance Monitor is a system monitoring tool on Windows that you can use to view real-time statistics about the applications you are running. But sometimes this tool fails to work correctly. If you're facing such a problem on your computer, here are a few fixes you can try to solve it.

## 1\. Reboot your Computer

 Whether you're experiencing performance issues such as slow startup times, or if Performance Monitor isn't working on your system, a simple reboot might do the trick.

 Rebooting Windows clears out any conflicting programs or services that may be causing PerfMon to not work properly. It removes any unnecessary data stored in memory that might be responsible for the issue.

To restart your computer, follow these steps:

1. Open the**Start** menu.
2. Click on the Power button, then select**Restart** .

 Once the computer has restarted, open Performance Monitor and check if the issue has been resolved.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Restart the Performance Logs and Alerts service

 If rebooting your computer doesn't fix the problem, you can try restarting the Performance Logs and Alerts service. This service is responsible for monitoring system performance settings and generating alert messages when something is wrong.

To restart this service, follow these steps:

1. Press**Win + R** on your keyboard to open the Run command
2. Type**services.msc** in the dialog box and press**Enter** .
3. In the Services window, scroll down to**Performance Logs & Alerts** service.
4. Right-click on the service and select the**Restart** option.  
![Restart Performance service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/restart-performance-service.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->

 After you follow the above steps, check if Performance Monitor is working correctly.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Run the System File Checker

 The System File Checker is a handy Windows tool that can scan for and fix corrupted system files. It is useful when the Performance Monitor isn't working due to a corrupt system file.

To run the System File Checker, follow these steps:

1. Click on the Start menu.
2. Type**cmd** in the search bar, then press**Ctrl + Shift + Enter** to open an elevated Command Prompt.
3. If UAC appears on the screen, click**Yes** to grant access. You can learn more about this handy tool with our [beginner's guide to the Windows Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) .  
![Run SFC Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-sfc-command.jpg)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
4. In the Command Prompt, type the following command and press**Enter** :  
sfc /scannow
5. The scan will check for any corrupted system files and repair them.

 After the scan is complete, restart your computer and check if Performance Monitor is working properly.

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
## 4\. Check for a Windows Update

 In some cases, outdated versions of Windows can cause Performance Monitor problems. To ensure your system is running the latest version of Windows, follow these steps:

1. Press**Win + I** on your keyboard to open System Settings. We also have an in-depth tutorial on [accessing the Settings menu](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Click**Windows Update** in the left pane.  
![Check for Updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/check-for-updates.jpg)
3. Then click the**Check for updates** button.

 If any available updates are found, Windows will download and install them automatically. After the updates have been installed, restart your computer and check if Performance Monitor is now working correctly.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
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






