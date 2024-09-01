---
title: "Realign Windows Clock: Stop Time Discrepancy Woes"
date: 2024-08-31T22:09:12.779Z
updated: 2024-09-01T22:09:12.779Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Realign Windows Clock: Stop Time Discrepancy Woes"
excerpt: "This Article Describes Realign Windows Clock: Stop Time Discrepancy Woes"
keywords: Fix Window Time Error,Stop Clock Misalignment,Realign Windows Timer,Correct Time Display,Resolve Time Discrepancy,Adjust Windows Clock,Eliminate Time Mismatch
thumbnail: https://thmb.techidaily.com/a69a15798572265a2574284260281ddf651b6e2edc67c914e7a3a40f4a1feb7f.png
---

## Realign Windows Clock: Stop Time Discrepancy Woes

 Is your Windows system clock out of sync? Are you receiving an error message saying “Time synchronization failed”? It may cause various issues like missing reminders or emails with the wrong timestamp. Read this guide to learn how to fix the issue and synchronize your system clock accurately.

## What Causes Time Synchronization to Fail on Windows?

 Time synchronization issues on Windows can occur for several reasons. Here are some common causes.

1. **Incorrect timezone settings:** The time set on your PC must be accurate for synchronization to work properly. If the time zone is incorrect, synchronization will fail.
2. **Firewall settings:** Firewalls block the Windows Time service from connecting to its hosts. This prevents time synchronization from occurring.
3. **System viruses and malware:** Viruses or malicious software corrupt system files related to time synchronization, causing failure.
4. **Problems with the Windows Time service:** The Windows Time (W32Time) service controls time synchronization on your system. If it's not running properly, synchronization will fail.

 Now that you know the possible causes of time synchronization failure, let’s discuss how to fix this issue.

## 1\. Restart the Windows Time Service

 The Windows Time Service keeps the computer’s time and date synchronized with other computers on the network. If this service is stopped or not functioning, it leads to time synchronization issues.

 To restart the Windows Time Service, follow these steps:

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **services.msc** in the search box and hit Enter. This will open the Services window.
3. Locate the **Windows Time** service and right-click on it.
4. Select **Restart** from the context menu.  
![Restart Windows Time service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restart-windows-time-service.jpg)

 Once the service is restarted, close the window and check the time synchronization.

## 2\. Configure the Windows Time Service

 If restarting the Windows Time Service doesn't resolve the time synchronization issue, configure its settings to see if that helps.

 To configure the Windows Time Service, follow these steps:

1. [Open the Services window](https://www.makeuseof.com/windows-11-open-services-app/).
2. Double-click on **Windows Time** to open its properties window.
3. On the **General** tab, set the Startup Typeto **Automatic**.  
![Windows Time Service Status](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-time-service-status.jpg)
4. Now go to Service Status and click on the **Start** button. If the service is running, click on **Stop** and then **Start**.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->
5. Switch to the **Log On** tab and select **Local System account**.  
![Windows Time Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-time-properties-window.jpg)
6. Check the **Allow Service** **to Interact with desktop** option.
7. Click **Apply > OK** to save the changes.

 Now that you have configured the Windows Time Service, close the window. After that, restart your computer and check if time synchronization works.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Change the Time Server

 This method is suitable when the time synchronization service fails to sync with an internet time server. It syncs to a reliable internet clock manually.

 To modify internet time settings, follow these steps:

1. [Open the Run Command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **timedate.cpl** in the text box and press Enter. This will open the Date and Time window.
3. Switch to the **Internet Time** tab and click on **Change settings**.
4. Check the box next to **Synchronize with an Internet time server**.  
![Change the Time Server](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/change-the-time-server.jpg)
5. Select a different time server from the **Server** list.
6. Click **Update now** to sync your PC with the selected time server.

 Once you perform the above action, close all windows and restart your computer. After restarting, check if the time synchronization issue is fixed.

## 4\. Add More Time Servers

 If changing the time server doesn't work, add more servers to the list. That way, Windows try different servers to keep time in sync. To add more time servers, follow these steps:

1. Press **Win + S** on your keyboard to open the Windows Search box.
2. Type **regedit** in the search box and hit Enter.
3. If UAC (User Account Control) dialog appears, click **Yes** to continue.
4. In the registry editor, navigate the following steps.  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\DateTime\Servers`
5. Right-click on the **Servers** key and select **New** \> **String Value**.  
![Add More Time Servers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/add-more-time-servers.jpg)
6. Name the new string value **ServerX**, where X is the server number.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
7. Double-click on the new **String Value** and enter a valid time server URL in the Value data box.
8. Repeat the above steps until you have added all the time servers to the list.

 Once you are done, close the registry editor. After synchronization completes, close all windows and restart your computer. Then verify if the time is accurate.

## 5\. Scan for Malicious Programs

 If other methods fail to fix the time synchronization issue on your Windows computer, scan for malicious programs. Malicious software interrupts time synchronization processes and causes errors.

 To scan for malicious programs, follow these steps:

1. Press **Win + S** on your keyboard to open the Windows Search box.
2. Type **Windows Security** in the search box and hit Enter.
3. In the Windows Security window, click on **Virus & threat protection**.  
![Scan options in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/scan-options-in-windows-security.jpg)
4. Under **Current threats**, click **Scan options** and check **Full scan** from the list.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)
5. Now click **Scan now** to initiate a full scan.
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->

 Once you perform the above action, close the Windows Security window and restart your computer. If malicious programs were responsible for the issue, it should now keep the time synchronized correctly.

## 6\. Try Some Generic Fixes

 Besides the specific solutions mentioned above, there are some general fixes that troubleshoot time synchronization problems.

 Try these suggestions to fix time synchronization failed errors:

1. [Run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/). This tool scans system files and replaces any corrupted files that cause the time synchronization to fail.
2. [Perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) and check if that helps. It’s possible that some software or process running on your PC interferes with time synchronization. Doing a clean boot identifies the culprit and solves the issue.
3. [Temporarily disable firewall and antivirus programs](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/). Firewall or antivirus settings can sometimes block the Windows Time service from connecting to its hosts, resulting in synchronization failure. Temporarily disabling your firewall and antivirus programs can resolve this issue.
4. [Run the Windows Network Connections tool](https://www.makeuseof.com/windows-open-network-connections-tool/) to diagnose and repair network issues.

 These fixes resolve time synchronization problems on your Windows computer.

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
## Fixing Time Synchronization Issues on Windows

 We hope this article resolved any timing issues you encountered on your Windows computer. If the issue continues, perform a system restore. This reverses any recent modifications that could cause the issue. Meanwhile, it is advised to regularly backup your data in case of sudden system failures.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://location-social.techidaily.com/4-feasible-ways-to-fake-location-on-facebook-for-your-poco-f5-pro-5g-drfone-by-drfone-virtual-android/"><u>4 Feasible Ways to Fake Location on Facebook For your Poco F5 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://fox-blue.techidaily.com/adjust-your-android-images-right-here/"><u>Adjust Your Android Images Right Here</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/business-mastery-through-youtubes-top-ten-channels-for-2024/"><u>Business Mastery Through YouTube's Top Ten Channels for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/enhancing-classroom-learning-through-recorders/"><u>Enhancing Classroom Learning Through Recorders</u></a></li>
<li><a href="https://windows11.techidaily.com/file-trailblazing-in-windows-11-the-top-6-techniques-to-duplicate-paths/"><u>File Trailblazing in Windows 11: The Top 6 Techniques to Duplicate Paths</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-motorola-edgeplus-2023-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Motorola Edge+ (2023) in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-successfully-install-or-update-the-rndis-driver-in-windows-step-by-step-instructions/"><u>How to Successfully Install or Update the RNDIS Driver in Windows - Step-by-Step Instructions</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-harness-the-power-of-color-grading-a-guide-to-luts-in-photoshop-cs6/"><u>In 2024, Harness the Power of Color Grading  A Guide to LUTs in Photoshop CS6</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/iphone-head-to-head-comparison-unpacking-differences-between-iphone-15-plus-and-pro-max/"><u>IPhone Head-to-Head Comparison: Unpacking Differences Between iPhone 15 Plus and Pro Max.</u></a></li>
<li><a href="https://windows11.techidaily.com/keep-your-file-explorer-running-smoothly-in-windows-11/"><u>Keep Your File Explorer Running Smoothly in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-spotlight-screenshots-in-windows-os/"><u>Mastering Spotlight Screenshots in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-execution-codewords-for-apps/"><u>Navigating Through Execution Codewords for Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-virtualbox-usb-connectivity-glitches-and-errors/"><u>Navigating Through VirtualBox USB Connectivity Glitches & Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-file-limit-anomaly-in-windows/"><u>Overcoming File Limit Anomaly in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-interrupts-with-fixing-breakpoints/"><u>Overcoming Windows Interrupts with Fixing Breakpoints</u></a></li>
<li><a href="https://windows11.techidaily.com/perfecting-desktop-aesthetics-sticky-notes-on-w11w10/"><u>Perfecting Desktop Aesthetics: Sticky Notes on W11/W10</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-paste-feature-efficacy-in-win-11/"><u>Restoring Paste Feature Efficacy in Win 11</u></a></li>
<li><a href="https://article-files.techidaily.com/rethinking-windows-photo-viewer-usage-on-modern-os-for-2024/"><u>Rethinking Windows Photo Viewer Usage on Modern OS for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-your-full-screen-capture-predicament-with-snip-and-sketch/"><u>Solving Your Full-Screen Capture Predicament with Snip & Sketch</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-process-implementing-end-task-feature-on-window-manager-windows-11/"><u>Step-By Step Process: Implementing End Task Feature on Window Manager (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-adding-outlook-preview-to-windows-devices/"><u>Step-by-Step: Adding Outlook Preview to Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-tasks-like-pro-mastering-windows-11s-capabilities/"><u>Streamline Tasks Like Pro: Mastering Windows 11'S Capabilities</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-windows-troubleshooting-with-8-tips/"><u>Streamlining Windows Troubleshooting with 8 Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-excess-window-tasks-in-windows/"><u>Tackling Excess Window Tasks in Windows</u></a></li>
<li><a href="https://win-forum.techidaily.com/tackling-total-disk-usage-overflows-in-windows-10-a-comprehensive-approach/"><u>Tackling Total Disk Usage Overflows in Windows 10: A Comprehensive Approach</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-unstartable-speech-to-text-on-windows-systems/"><u>Tackling Unstartable Speech to Text on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/tailor-filenames-in-bulk-using-windows-powertools/"><u>Tailor Filenames in Bulk Using Windows PowerTools</u></a></li>
<li><a href="https://windows11.techidaily.com/the-complete-checklist-for-epic-launcher-savings/"><u>The Complete Checklist for Epic Launcher Savings</u></a></li>
<li><a href="https://windows11.techidaily.com/timely-troubleshooting-your-chrome-clock-glitch/"><u>Timely Troubleshooting: Your Chrome Clock Glitch</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-nvidia-cp-non-saving-on-win11/"><u>Troubleshooting Nvidia CP Non-Saving on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-sound-service-lag/"><u>Troubleshooting Windows Sound Service Lag</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-screen-management-guide-for-dual-displays/"><u>Windows 11 Screen Management Guide for Dual Displays</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-dormancy-practical-tips-and-tricks/"><u>Windows Dormancy: Practical Tips & Tricks</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>