---
title: Easy Ways to Revert Personalized Settings on Windows 11'S Search
date: 2024-06-25T11:55:41.790Z
updated: 2024-06-26T11:55:41.790Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Easy Ways to Revert Personalized Settings on Windows 11'S Search
excerpt: This Article Describes Easy Ways to Revert Personalized Settings on Windows 11'S Search
keywords: Win11 Search Reset,Personalize Restore Windows,Windows 11 Privacy Change,Revert Window Settings,Quick Search Options Fix,Customize Windows Search,Revive Search Preferences
thumbnail: https://thmb.techidaily.com/030f43c520c13566e766031892a27e4f35e056dc768bf0f9b9c3aff2261e980f.jpg
---

## Easy Ways to Revert Personalized Settings on Windows 11'S Search

 Like any other computer program, Windows Search can sometimes develop issues that require you to reset its settings to work properly. This article explains two simple ways to reset Windows Search settings back to default. Let's look at each one in detail.

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
7. Set the value to **0** and click **OK** to save the changes.

 If the SetupCompletedSuccessfully key is missing, you will have to manually create it. To do this, right-click on the Windows Search key and select **New > DWORD (32-bit) Value**. Name this newly created key as **SetupCompletedSuccessfully** and set its value to **0**.

 After performing the steps above, close the Registry Editor and restart your computer for the changes to take effect.

## 2\. Use Windows PowerShell

 If you prefer command-line solutions, you can use PowerShell to reset Windows Search settings. It involves running a few simple commands to restore search settings. Here's how to do it.

[Open the Microsoft Download Page](https://www.microsoft.com/en-us/download/100295) and download the ResetWindowsSearchBox.ps1 PowerShell script. Once downloaded, right-click on the file and select **Run with PowerShell**.

 If you see an error message _"Cannot be loaded because the running script is disabled on this system"_ you need to enable script execution first. To do that, [open PowerShell as a system administrator](http://www.makeuseof.com/windows-11-powershell-administrator/). Then type **Get-ExecutionPolicy** and press Enter.

![Restrict or Unrestrict the Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restrict-or-unrestrict-the-command.png)

 If the output is **Restricted**, execute the following command to allow PowerShell scripts:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted

 After setting the execution policy, try running the ResetWindowsSearchBox.ps1 file again. Once the script is executed successfully, it resets Windows search settings.

![Reset Windows Search Via PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-search-via-powershell.png)

 After resetting the Windows Search settings, you can restore the execution policy to its original settings. To do that, open PowerShell as an administrator again and execute the following command:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Restricted

 Once the execution policy is set back to its original value, restart your computer. The Windows Search settings should now be restored to their default state.

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
<li><a href="https://windows11.techidaily.com/guide-driver-verifier-management-in-windows-11/"><u>Guide: Driver Verifier Management in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-xbox-mic-issues-on-windows-1111-pro/"><u>Resolving Xbox Mic Issues on Windows 11/11 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/strip-onedrive-of-microsoft-id-integration-in-windows/"><u>Strip OneDrive of Microsoft ID Integration in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-error-0x80072f8f-0x20000-in-windows/"><u>Troubleshooting Error 0X80072f8f - 0X20000 in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-windows-11-stumbling-blocks-the-most-crucial-tips/"><u>Avoiding Windows 11 Stumbling Blocks: The Most Crucial Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/reintroduce-disappearing-5ghz-network-on-windows-11/"><u>Reintroduce Disappearing 5GHz Network on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-tasks-initiating-administrative-powershell-on-win11/"><u>Elevate Your Tasks: Initiating Administrative PowerShell on Win11</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/master-the-art-of-easy-webinar-recordings-windows-and-macos-advice-for-2024/"><u>Master the Art of Easy Webinar Recordings  Windows & macOS Advice for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-artisans-crafting-marvel-fantasy-landscapes/"><u>[New] Artisans Crafting Marvel Fantasy Landscapes</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-behind-the-magic-cinematic-technique-1-5-insights/"><u>[New] Behind the Magic  Cinematic Technique #1-5 Insights</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-transform-your-virtual-presence-with-google-meets-effects-features-for-2024/"><u>[New] Transform Your Virtual Presence with Google Meet's Effects Features for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-11-free-apps-to-check-imei-on-samsung-galaxy-m14-4g-phones-by-drfone-android/"><u>Top 11 Free Apps to Check IMEI on Samsung Galaxy M14 4G Phones</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-navigating-the-maze-of-private-snapshares/"><u>[Updated] 2024 Approved  Navigating the Maze of Private Snapshares</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-dialing-up-deliverables-a-comprehensive-guide-to-gainful-vlogging/"><u>[Updated] In 2024, Dialing Up Deliverables  A Comprehensive Guide to Gainful Vlogging</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-step-by-step-techniques-for-iphone-7-screen-saving/"><u>[New] Step-by-Step Techniques for iPhone 7 Screen Saving</u></a></li>
</ul></div>
