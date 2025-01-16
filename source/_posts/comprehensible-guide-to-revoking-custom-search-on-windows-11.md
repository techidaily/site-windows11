---
title: Comprehensible Guide to Revoking Custom Search on Windows 11
date: 2025-01-15T11:56:00.861Z
updated: 2025-01-16T05:15:58.700Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Comprehensible Guide to Revoking Custom Search on Windows 11
excerpt: This Article Describes Comprehensible Guide to Revoking Custom Search on Windows 11
keywords: Windows 11 Search Reset,Revoke Windows Custom Search,Clearing Search History W11,Disable Windows Personalized Search,Revoking SOS on Windows 11,Remove WinSearch Settings,Unset Personalized Windows Search
thumbnail: https://thmb.techidaily.com/85be9153d8c81024583588a94ed9e00fc880777ac2a8c7cff5efd5d21044d91c.jpg
---

## Comprehensible Guide to Revoking Custom Search on Windows 11

 Like any other computer program, Windows Search can sometimes develop issues that require you to reset its settings to work properly. This article explains two simple ways to reset Windows Search settings back to default. Let's look at each one in detail.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GFHH14XlFCk?si=2HcjQbDx5eG0ZQAt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Should You Reset Windows Search Settings?

 Windows Search tracks files and folders on your hard drive, so you can find them more quickly. However, over time search settings and preferences can become corrupted, leading to incorrect search results or slow performance. To get the most effective results from Windows Search, you should periodically reset your search settings.

 Resetting search settings on Windows can improve search speed and accuracy. It gets rid of useless data and resolves errors or conflicts due to stored information. This can ultimately enhance your computer’s performance and provide a more efficient search experience.

 Let's now explore how to reset Windows Search settings.

## 1\. Tweak the Registry Editor

 If you want to reset Windows Search settings back to default, you can modify the registry editor. It involves directly changing certain keys in the Windows Registry, which can sometimes become risky if done incorrectly.

 To avoid this issue, be sure to [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before proceeding. Once done, follow these steps.

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the dialog box and hit the Enter key.
3. When the UAC prompt appears on the screen, click **Yes** to continue.
4. In the Registry Editor window, navigate to the following path:  
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows Search  
 You can also copy and paste the path into the address bar at the top of the window and hit the Enter key. This will take you to the Windows Search section.
5. Now move to the right pane and search for the key named **SetupCompletedSuccessfully**.  
![Reset Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-search.jpg)
6. Select this key, right-click on it, and choose **Modify**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Set the value to **0** and click **OK** to save the changes.

 If the SetupCompletedSuccessfully key is missing, you will have to manually create it. To do this, right-click on the Windows Search key and select **New > DWORD (32-bit) Value**. Name this newly created key as **SetupCompletedSuccessfully** and set its value to **0**.

 After performing the steps above, close the Registry Editor and restart your computer for the changes to take effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l4R7_qNIQvY?si=2zJOPfEcm6_3udzn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Use Windows PowerShell

 If you prefer command-line solutions, you can use PowerShell to reset Windows Search settings. It involves running a few simple commands to restore search settings. Here's how to do it.

[Open the Microsoft Download Page](https://www.microsoft.com/en-us/download/100295) and download the ResetWindowsSearchBox.ps1 PowerShell script. Once downloaded, right-click on the file and select **Run with PowerShell**.

 If you see an error message _"Cannot be loaded because the running script is disabled on this system"_ you need to enable script execution first. To do that, [open PowerShell as a system administrator](http://www.makeuseof.com/windows-11-powershell-administrator/). Then type **Get-ExecutionPolicy** and press Enter.

![Restrict or Unrestrict the Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restrict-or-unrestrict-the-command.png)

 If the output is **Restricted**, execute the following command to allow PowerShell scripts:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted

 After setting the execution policy, try running the ResetWindowsSearchBox.ps1 file again. Once the script is executed successfully, it resets Windows search settings.

![Reset Windows Search Via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-search-via-powershell.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ME5-sAQJVE4?si=ZfcvJSnhQevWtjI0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After resetting the Windows Search settings, you can restore the execution policy to its original settings. To do that, open PowerShell as an administrator again and execute the following command:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Restricted

 Once the execution policy is set back to its original value, restart your computer. The Windows Search settings should now be restored to their default state.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qv4Qm7kpeMs?si=9fv5SOS5a2DvixTK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Easy Ways to Reset Windows Search

 Resetting Windows search settings can fix any issues you may have with your search experience. This guide will teach you how to reset Windows Search settings to their original values.

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
<li><a href="https://extra-resources.techidaily.com/updated-capturing-the-horizon-expert-techniques-in-drone-filmmaking/"><u>[Updated] Capturing the Horizon Expert Techniques in Drone Filmmaking</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-cutting-down-video-lengths-the-ultimate-mac-guide-for-insta/"><u>2024 Approved Cutting Down Video Lengths The Ultimate Mac Guide for Insta</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/budget-friendly-power-station-revolutionizes-road-trips-a-firsthand-review-zdnet/"><u>Budget-Friendly Power Station Revolutionizes Road Trips: A Firsthand Review - ZDNet</u></a></li>
<li><a href="https://win-amazing.techidaily.com/comprehensive-guide-to-solving-lg-monitor-driver-glitches-on-older-windows-os-versions/"><u>Comprehensive Guide to Solving LG Monitor Driver Glitches on Older Windows OS Versions</u></a></li>
<li><a href="https://facebook.techidaily.com/determining-facebook-uptime-methods-and-timelines/"><u>Determining Facebook Uptime: Methods and Timelines</u></a></li>
<li><a href="https://extra-information.techidaily.com/laugh-loom-image-stitcher/"><u>Laugh Loom Image Stitcher</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-dormant-backup-service-on-os-x/"><u>Recovering Dormant Backup Service on OS X</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-windows-upgrades-mastering-the-installation-of-elusive-features/"><u>Seamless Windows Upgrades: Mastering the Installation of Elusive Features</u></a></li>
<li><a href="https://facebook.techidaily.com/seeing-through-the-hype-a-fresh-perspective-on-fb-documents/"><u>Seeing Through the Hype: A Fresh Perspective on FB Documents</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-overcome-upgrade-errors-on-windows-11-systems/"><u>Steps to Overcome Upgrade Errors on Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/switching-off-geforce-ui-in-windows-settings/"><u>Switching Off GeForce UI in Windows Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-w11-calendar-and-mail-an-essential-tutorial/"><u>Unlocking W11 Calendar & Mail: An Essential Tutorial</u></a></li>
<li><a href="https://buynow-info.techidaily.com/viair-88p-compact-air-compressor-examined-exceptional-strength-with-some-minor-constraints/"><u>Viair 88P Compact Air Compressor Examined - Exceptional Strength with Some Minor Constraints</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-woes-no-more-essential-fixers-ranked/"><u>Windows Woes No More: Essential Fixers Ranked</u></a></li>
</ul></div>

