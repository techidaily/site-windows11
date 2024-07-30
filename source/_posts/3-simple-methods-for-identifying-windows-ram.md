---
title: 3 Simple Methods for Identifying Windows RAM
date: 2024-07-29T04:21:57.785Z
updated: 2024-07-30T04:21:57.785Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 3 Simple Methods for Identifying Windows RAM
excerpt: This Article Describes 3 Simple Methods for Identifying Windows RAM
keywords: Windows Memory Test,RAM Detection Tips,RAM Quality Check,Detecting Windows RAM,RAM Performance Guide,Simple RAM Verify,Identify Windows RAM
thumbnail: https://thmb.techidaily.com/700293ffdf9a4730d9df7fa5093979f42d9fa58b0347dc31082bc6c29ca2c642.jpg
---

## 3 Simple Methods for Identifying Windows RAM

 Knowing the type of RAM installed on your Windows PC can help you make more informed decisions when upgrading or diagnosing performance issues. Thankfully, it’s possible to check the RAM type on your Windows PC without opening the computer case and getting your hands dirty.

 This guide will walk you through some easy methods for identifying the type of RAM housed within your computer.

## 1\. How to Check the RAM Type With Command Prompt

 The most straightforward to check the RAM type on your Windows PC is via Command Prompt. You can use this method even [if you're a beginner with the Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/), as it only requires you to run a single command.

 Here's how you can check the RAM type on Windows using the Command Prompt:

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the menu that appears.
2. Select **Yes** when the User Account Control (UAC) prompt appears.
3. In the console, type the command mentioned below and press **Enter**.  
`wmic memorychip get devicelocator, memorytype`
4. Note down the code number under the **MemoryType** column.  
![Check Memory Type Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-command-prompt.jpg)

 Compare the numerical value from the **MemoryType** column with the following table to identify the RAM type. For instance, if the code number is **24**, it means your computer has **DDR3** RAM.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
![A Table Showing RAM Type and Numeric Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/a-table-showing-ram-type-and-numeric-value.jpg)

## 2\. How to Check the RAM Type With PowerShell

 Like Command Prompt, you can use PowerShell to find out the type of RAM installed on your Windows computer. Here are the steps for the same.

1. Press **Win + S** to open the search menu.
2. Type **powershell** in the box.
3. Select **Run as administrator**.
4. When the User Account Control (UAC) prompt appears, select **Yes** to continue.
5. Type the following command in the PowerShell window and hit **Enter**.  
`Get-CimInstance -ClassName Win32_PhysicalMemory | Format-Table SMBIOSMemoryType`  
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Check RAM Type Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-ram-type-using-powershell.jpg)

 Under the **SMBIOSMemoryType** column, note down the code number and compare it with the following table to determine the RAM type.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![A Table Showing RAM Type and Numeric Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/a-table-showing-ram-type-and-numeric-value.jpg)

## 3\. How to Check the RAM Type Using the Task Manager App

 Windows Task Manager can provide you with all the necessary hardware information you need about your PC, including the type of RAM installed. However, it's important to note that Task Manager does not show the memory type if your PC has [DDR4 or DDR5 RAM](https://www.makeuseof.com/ddr4-vs-ddr5-should-you-upgrade/). So, this method will only work for PCs with DDR3 or lower-generation RAM.

 To check the RAM type using Windows Task Manager, follow these steps:

1. Press **Ctrl + Shift + Esc** to open the Task Manager.
2. Switch to the **Performance** tab.
3. Select **Memory** from the left pane. You should see the amount and type of RAM your PC has in the top right corner of the screen.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
![Check Memory Type Using Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-windows-task-manager.jpg)

 The Windows Task Manager does more than show hardware information. You also use it to manage running programs, end tasks, and view resource usage. To learn more, read our guide on the best [Windows Task Manager tips that you may not know](https://www.makeuseof.com/tag/10-windows-task-manager-tricks-didnt-know/).

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## 4\. How to Check the RAM Type Using CPU-Z

 If you're seeking a relatively uncomplicated method to check the RAM type along with other hardware details, you can use a third-party app like CPU-Z. It is available for free and allows you to access various sets of information about your computer, including details about both the CPU and the RAM.

 Download and open the [CPU-Z](https://www.cpuid.com/softwares/cpu-z.html) app on your PC. Click on the **Memory** tab to get a detailed breakdown of the installed RAM. Under the **General** section, look for the value in the **Type** field to know the type of RAM installed on your PC.

![Check Memory Type Using CPU-Z App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-cpu-z-app.jpg)

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Know the Type of RAM Installed on Your Windows PC

 The performance of your computer is affected not only by the amount of RAM installed but also by the type of RAM. Fortunately, identifying the RAM type on your Windows PC is a quick and painless process with the methods mentioned above.

 This guide will walk you through some easy methods for identifying the type of RAM housed within your computer.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-knowledge.techidaily.com/new-immersive-android-viewer-for-high-quality-3d/"><u>[New] Immersive Android Viewer for High-Quality 3D</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-how-to-edit-youtube-videos-in-imovie/"><u>[New] In 2024, How to Edit YouTube Videos in iMovie?</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-practical-measures-for-capturing-vimeo-videos-for-2024/"><u>[New] Practical Measures for Capturing Vimeo Videos for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-quick-tips-turning-off-igtv/"><u>[Updated] Quick Tips  Turning Off IGTV</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-the-ultimate-guide-to-displaying-screens-in-google-meet/"><u>[Updated] The Ultimate Guide to Displaying Screens in Google Meet</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-direct-access-for-the-curious-explorer-in-windows-11/"><u>A Guide to Direct Access for the Curious Explorer in Windows 11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/choose-your-winner-dji-gopro-max-instax-x3-for-2024/"><u>Choose Your Winner  DJi, GoPro Max, Instax X3 for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-pictures-files-on-honor-x50i-by-fonelab-android-recover-pictures/"><u>Complete guide for recovering pictures files on Honor X50i.</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-resource-scheduling-for-android-on-windows-wsl/"><u>Efficient Resource Scheduling for Android on Windows WSL</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-your-windows-onedrive-hurdles-now/"><u>Fix Your Windows OneDrive Hurdles Now</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-common-issues-for-intel-unison-on-windows-11/"><u>Fixing Common Issues for Intel Unison on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-11-nvidia-cp-not-opening-problem/"><u>Fixing Windows 11: Nvidia CP Not Opening Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-1110-how-to-stop-double-click-folders-from-closing/"><u>Fixing Windows 11/10: How to Stop Double-Click Folders From Closing</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-handle-exception-breaking-point-issues-on-pc/"><u>How to Handle Exception Breaking Point Issues on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/ignite-vm-speed-and-stability-top-6-methods-to-enhance-in-windows/"><u>Ignite VM Speed and Stability: Top 6 Methods to Enhance in Windows</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-poco-x5-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Poco X5 Pro | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-icloud-by-checkra1n-even-on-apple-iphone-x-if-youve-tried-everything-by-drfone-ios/"><u>In 2024, How To Bypass iCloud By Checkra1n Even On Apple iPhone X If Youve Tried Everything</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-card-on-iphone-14-pro-max-online-without-jailbreak-by-drfone-ios/"><u>In 2024, How to Unlock SIM Card on iPhone 14 Pro Max online without jailbreak</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-preparing-for-departure-leaving-your-discord-circle/"><u>In 2024, Preparing for Departure  Leaving Your Discord Circle</u></a></li>
<li><a href="https://windows11.techidaily.com/instructional-guide-for-end-task-enabling-on-windows-11/"><u>Instructional Guide for End Task Enabling on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/integrated-thermal-management-windows-edition/"><u>Integrated Thermal Management: Windows Edition</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-interactions-between-devices-and-pc-slumber/"><u>Navigating Interactions Between Devices and PC Slumber</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-not-found-errors-on-pc-windows/"><u>Overcoming 'Not Found' Errors on PC Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/prioritize-your-data-spotting-the-biggest-disk-space-eaters/"><u>Prioritize Your Data: Spotting the Biggest Disk Space Eaters</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-system-limitations-intel-hd-graphics-compatibility-fixes/"><u>Rectifying System Limitations: Intel HD Graphics Compatibility Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/reducing-heavy-resource-use-by-news-apps-in-windows-os/"><u>Reducing Heavy Resource Use by News Apps in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/resetting-grammarly-settings-in-windows/"><u>Resetting Grammarly Settings in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-geforce-experience-setting-retrieval-failure-on-windows-1111/"><u>Resolving 'GeForce Experience' Setting Retrieval Failure on Windows 11/11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-license-validity-alert-on-windows-oses/"><u>Resolving License Validity Alert on Windows OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-sound-and-microphone-discrepancies-in-valorant/"><u>Resolving Sound and Microphone Discrepancies in Valorant</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-oculus-rift-as-a-windows-pc-vr-setup/"><u>Setting up Oculus Rift as a Windows PC VR Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-start-driver-verifier-manager/"><u>Steps to Start Driver Verifier Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-to-the-windows-too-many-requests-challenge/"><u>Swift Solutions to the Windows Too Many Requests Challenge</u></a></li>
<li><a href="https://windows11.techidaily.com/synchronize-the-seconds-windows-time-repair-guide/"><u>Synchronize the Seconds: Windows Time Repair Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/system-saviors-the-10-best-windows-diagnostic-apps/"><u>System Saviors: The 10 Best Windows Diagnostic Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-high-memory-consumption-in-edges-webview2/"><u>Tackling High Memory Consumption in Edge's WebView2</u></a></li>
<li><a href="https://windows11.techidaily.com/thawing-the-frozen-menus-6-windows-remedies-explored/"><u>Thawing the Frozen Menus: 6 Windows Remedies Explored</u></a></li>
<li><a href="https://windows11.techidaily.com/uninstalling-the-default-software-on-win11-pcs/"><u>Uninstalling the Default Software on Win11 PCs</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/urban-pursuit-without-the-need-for-gta-for-2024/"><u>Urban Pursuit Without the Need for GTA for 2024</u></a></li>
</ul></div>
