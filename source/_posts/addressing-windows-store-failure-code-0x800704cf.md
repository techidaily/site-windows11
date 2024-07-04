---
title: Addressing Windows Store Failure Code 0X800704CF
date: 2024-07-03T11:10:08.135Z
updated: 2024-07-04T11:10:08.135Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Windows Store Failure Code 0X800704CF
excerpt: This Article Describes Addressing Windows Store Failure Code 0X800704CF
keywords: WinStoreErrorCode0xCF,XASFailureWindows,ErrorCode0X800704CF,StoreAppFailure0XCF,WindowsOSWinStoreError,0X800704CFApplication,Win10Store0xCFIssue
thumbnail: https://thmb.techidaily.com/f66305bee95e2c8cfda71737bc488d60f6c275330b2e729ec458216f465e024e.png
---

## Addressing Windows Store Failure Code 0X800704CF

 Many Microsoft Store users have reported they can’t use the app in both Windows 10 and 11 because of error 0x800704CF. Error 0x800704CF occurs when those users attempt to log into Microsoft Store. Its error message says, “You’ll need the internet for this… 0x800704CF.” This issue arises even when users are connected to the internet and can open web pages.

 Thus, error 0x800704CF is seemingly a Microsoft Store connection issue that renders the app inoperative in Windows 11 and 10\. If you're facing this issue this is how you can resolve error 0x800704CF.

## 1\. Run the Internet Connection and Network Adapters Troubleshooters

 Windows 11 and 10 have a handy collection of troubleshooters that can be a good starting point for fixing many issues. The Internet Connection and Network Adapters troubleshooters could be useful for resolving error 0x800704CF. You can access those troubleshooters via the Control Panel in Windows 11 and 10 as follows:

1. Press**Win + R** at the same time to launch a Run dialog accessory.
2. Input Control Panel in Run and click**OK** .
3. Select the**Large icons** option on Control Panel’s**View by** menu.  
![The Control Panel's large icon view](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/control-panel.jpg)
4. Click**Troubleshooting** to access that applet.
5. Select the**View all** option to see the full list of troubleshooters.  
![The troubleshooting list](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/troubleshooter-list.jpg)
6. Then double-click**Internet Connections** or**Network Adapter** to open one of those troubleshooters.  
![The troubleshooting list](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/troubleshooter-list.jpg)
7. Click**Next** in those troubleshooters and apply any potential fixes suggested.

 Windows Store App is also a troubleshooting tool that could be useful for addressing error 0x800704CF. That one might fix issues with the Microsoft Store app. So, consider running that troubleshooter as well if the others don't provide a fix.

## 2\. Repair and Reset the Microsoft Store App

 Windows has two troubleshooting options for fixing Microsoft Store when it’s not working right. Those Repair and Reset options can resolve all kinds of app bugs and corruption errors. So, those options could feasibly resolve error 0x800704CF for some users. Check out our guide about [how to reset apps in Windows](https://www.makeuseof.com/windows-reset-app/) for details about how to apply this resolution.

![The Reset and Repair buttons](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/repair-button.jpg)

## 3\. Set a Different DNS Server

 Changing DNS server settings is a resolution that’s worked for some users who’ve needed to fix error 0x800704CF. To apply this solution, change your PC’s DNS server to Google via the Control Panel. Our guide for [how to change your DNS server](https://www.makeuseof.com/windows-11-alternate-ways-change-dns-server-settings/) includes step-by-step instructions for how to do that along with the required Google DNS addresses.

![DNS server settings on the Internet Protocol Version window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/internet-protocal-window.jpg)

## 4\. Execute the Remove Proxy Server Command

 Another confirmed method for fixing error 0x800704CF is to run a command for removing the proxy server. Users who’ve confirmed this potential solution ran the Netsh.exe utility to disable proxy, which sets more direct internet access. This is how you can remove the proxy server with the Command Prompt:

1. First, locate the Command Prompt by opening the search box (press**Win** +**S**) and inputting cmd.
2. Open Command Prompt with elevated privileges by clicking a**Run as administrator** option for that app inside the search tool.
3. Input the Netsch.exe command and hit**Enter** :  
`netsh winhttp reset proxy`  
![The remove proxy command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/remove-proxy-command.jpg)
4. Restart Windows 11 or 10 after executing the command.

## 5\. Disable the Microsoft Network Component Setting Client

 Some users have been able to fix error 0x800704CF by disabling the**Microsoft Network Connection** setting, which is enabled by default. It’s ok to disable that component for your connection so long as you don’t need to access resources on a Microsoft network. You can disable the**Client for Microsoft Network** option as follows:

1. Open the Run dialog with the**Win +** **R** key combination.
2. Type input**ncpa.cpl** inside Run.
3. Click**OK** to access the Network Connections Control Panel applet.
4. Right-click your internet network adapter to select a**Properties** option for it.  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/properties-option2.jpg)
5. Deselect the**Client for Microsoft Networks** checkbox.  
![The Client for Microsoft Networks checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/client-for-microsoft-network-option.jpg)
6. Select**OK** to save the new property setting, and restart your computer.

## 6\. Reinstall the Network Adapter Driver

 Error 0x800704CF can occur because of a network adapter driver issue. If your PC’s network driver is faulty, reinstalling it could be the potential solution for you. Try reinstalling your PC’s network adapter driver like this:

1. Use one of the many [ways to open Device Manager](https://www.makeuseof.com/windows-open-device-manager/) and expand the**Network adapters** category.
2. Then right-click your PC’s internet network adapter to select an**Uninstall** **device** option for it.  
![The Uninstall device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/properties-context-menu-option.jpg)
3. Select the**Delete the driver** (or**Attempt to remove the driver**) checkbox.
4. ![The Delete the driver software for this device checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/uninstall-device-window.jpg)  
 Click**Uninstall** inside the confirmation dialog window.
5. To reinstall, click the**Action** menu.  
![The Scan for hardware changes option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/scan-for-hardware-changes.jpg)
6. Select**Scan for hardware changes** on the menu to detect and reinstall the missing network driver.

## 7\. Reregister the Microsoft Store App

 Reregistering the Microsoft Store app will reset it to a default configuration, which is the closest thing to reinstalling that app (it doesn’t have an option for uninstalling).

 To apply this solution, open Command Prompt with admin rights, as outlined in steps one and two of resolution four in this guide. Then execute this command:

`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml&}`

## 8\. Reset Your PC’s Network

 Another potential cause of error 0x800704CF is misconfigured network settings. To address such a potential cause, you can reset your PC’s network components to default settings. Doing so also reinstalls network adapters.

![The Network Reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/network-reset-option.jpg)

 A network reset will erase saved connection details. So, make sure you’ve got your network password handy for re-establishing your connection. Our [how to reset your network settings on Windows](https://www.makeuseof.com/reset-network-settings-windows-11/) guide tells you how to apply this possible error 0x800704CF solution in Windows 11\. Fortunately, the steps for Windows 10 are the same.

## 9\. Set Up an Alternative User Account

 You might need to fix error 0x800704CF because of an issue with your current user account. Some Windows troubleshooting tools could feasibly resolve that user account glitch. However, setting up and migrating to a new user account is an alternative troubleshooting method that you can try.

![The Add account button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-account-option2.jpg)

 To apply this solution, check out our post for [resolving Windows issues by setting up a new user account](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) . Create a new local user account as instructed in that article, and then log in to the new account to see if error 0x800704CF occurs there. If not, you can migrate your user files to the new account as covered in that guide.

## Get Microsoft Store Error 0x800704CF Sorted on Your PC

 Error 0x800704CF can be a taxing issue to resolve in Windows. It can seemingly arise because of networking, the Microsoft Store app, and Windows account issues, which makes troubleshooting that issue a bit of a slog. However, the troubleshooting methods outlined above will probably get error 0x800704CF sorted on most users’ PCs.

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/restoring-league-of-legends-playability-on-pc/"><u>Restoring League of Legends Playability on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-chromes-mistaken-malware-detection-errors-in-windows/"><u>Fixing Chrome’s Mistaken Malware Detection Errors in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/cost-effective-solutions-affordable-windows-11-key-access/"><u>Cost-Effective Solutions: Affordable Windows 11 Key Access</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-disabling-onedrive-icon-on-windows-11-explore/"><u>Strategies for Disabling OneDrive Icon on Windows 11 Explore</u></a></li>
<li><a href="https://windows11.techidaily.com/checking-for-safe-network-connections-on-windows/"><u>Checking for Safe Network Connections on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-perfect-icon-placement/"><u>Strategies for Perfect Icon Placement</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-solution-for-inaccessible-administrative-mode/"><u>Comprehensive Solution for Inaccessible Administrative Mode</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-the-ultimate-guide-to-recording-your-desktop-with-filmora-scrn-for-2024/"><u>Updated The Ultimate Guide to Recording Your Desktop with Filmora Scrn for 2024</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-social-media-stardom-guide-for-2024/"><u>[New] Social Media Stardom Guide for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-oneplus-nord-3-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 4 solution to get rid of pokemon fail to detect location On OnePlus Nord 3 5G | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-ideal-tools-for-creating-animation-with-models/"><u>[New] Ideal Tools for Creating Animation with Models</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/step-by-step-guide-to-creating-popular-youtube-openings-for-2024/"><u>Step-by-Step Guide to Creating Popular YouTube Openings for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-streamline-team-conferencing-via-discords-screen-sharing-for-2024/"><u>[New] Streamline Team Conferencing via Discord's Screen Sharing for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-minecraft-domicile-easy-to-build-residential-plans/"><u>In 2024, Minecraft Domicile  Easy-To-Build Residential Plans</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/igh-quality-video-capture-for-beginner-creators-for-2024/"><u>[New] High-Quality Video Capture for Beginner Creators for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-realme-12-pro-5g-phone-password-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock Realme 12 Pro 5G Phone Password Without Factory Reset?</u></a></li>
</ul></div>
