---
title: "Instant Fix: Resetting Windows 11 Search Preferences"
date: 2024-12-07T18:20:14.025Z
updated: 2024-12-10T18:48:23.810Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Instant Fix: Resetting Windows 11 Search Preferences"
excerpt: "This Article Describes Instant Fix: Resetting Windows 11 Search Preferences"
keywords: Windows 11 Reset,Search Settings Fix,PC Search Reset,Windows Search Change,Update Search Pref,Windows Search Reset,Quick Windows Search
thumbnail: https://thmb.techidaily.com/86c324ce76532279df624a7b580daa3d859103088f02a9b5a61fe37bc90c745a.png
---

## Instant Fix: Resetting Windows 11 Search Preferences

 Like any other computer program, Windows Search can sometimes develop issues that require you to reset its settings to work properly. This article explains two simple ways to reset Windows Search settings back to default. Let's look at each one in detail.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LI9nKlbhnw8?si=uUXFVbuEqXtFHHv0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Should You Reset Windows Search Settings?

 Windows Search tracks files and folders on your hard drive, so you can find them more quickly. However, over time search settings and preferences can become corrupted, leading to incorrect search results or slow performance. To get the most effective results from Windows Search, you should periodically reset your search settings.

 Resetting search settings on Windows can improve search speed and accuracy. It gets rid of useless data and resolves errors or conflicts due to stored information. This can ultimately enhance your computer’s performance and provide a more efficient search experience.

 Let's now explore how to reset Windows Search settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2NU63YqpVqw?si=uoJs0-nZYAkILqXx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/M5pwd2mwaQQ?si=qyZHgdTlbQbc32Mp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After resetting the Windows Search settings, you can restore the execution policy to its original settings. To do that, open PowerShell as an administrator again and execute the following command:

Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Restricted

 Once the execution policy is set back to its original value, restart your computer. The Windows Search settings should now be restored to their default state.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_1g4U13PBk0?si=xJLJtlc4hKBTBH8M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-recording.techidaily.com/new-broadcast-battles-obs-clashes-with-shadowgl-for-2024/"><u>[New] Broadcast Battles OBS Clashes with ShadowGL for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-narratives-before-night-an-analysis-of-storytelling-videos/"><u>[Updated] 2024 Approved Narratives Before Night An Analysis of Storytelling Videos</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-simplified-approaches-to-insta-photovideo-resharing/"><u>[Updated] In 2024, Simplified Approaches to Insta Photo/Video Resharing</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/bitevideo-innovator/"><u>BiteVideo Innovator</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-frp-from-vivo-y28-5g-by-drfone-android/"><u>How to Bypass FRP from Vivo Y28 5G?</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-entry-point-not-found-error-on-windows/"><u>How to Fix the Entry Point Not Found Error on Windows</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-14-to-other-iphone-15-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 14 To Other iPhone 15 devices? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-through-windows-key-settings-easily/"><u>Navigate Through Windows Key Settings Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/prolific-tools-in-windows-11-top-7-productivity-widgets/"><u>Prolific Tools in Windows 11: Top 7 Productivity Widgets</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-windows-11-setup-without-internet/"><u>Step-by-Step: Windows 11 Setup Without Internet</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-printer-service-disabled-message-in-winos/"><u>Tackling Printer Service Disabled Message in WinOS</u></a></li>
<li><a href="https://tech-revival.techidaily.com/ultimate-walkthrough-for-discontinuing-access-to-chatgpt-services/"><u>Ultimate Walkthrough for Discontinuing Access to ChatGPT Services</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-the-other-users-microsoft-account-problem/"><u>Unblocking the Other User’s Microsoft Account Problem</u></a></li>
</ul></div>

