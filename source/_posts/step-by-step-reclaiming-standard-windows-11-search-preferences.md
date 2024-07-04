---
title: "Step-by-Step: Reclaiming Standard Windows 11 Search Preferences"
date: 2024-06-25T12:23:24.940Z
updated: 2024-06-26T12:23:24.940Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Step-by-Step: Reclaiming Standard Windows 11 Search Preferences"
excerpt: "This Article Describes Step-by-Step: Reclaiming Standard Windows 11 Search Preferences"
keywords: Win11 Search Guide,Customize Windows 11,Set Win11 Search,Default Win11 Search,Modify Windows 11 Search,Windows 11 Preferences,Restore Win11 Settings
thumbnail: https://thmb.techidaily.com/2e81f992123e17db59f89c6842ca48bb426d509215d95604071818ec4e7dc281.jpg
---

## Step-by-Step: Reclaiming Standard Windows 11 Search Preferences

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
<li><a href="https://windows11.techidaily.com/mastery-over-malfunctioning-windows-easy-fixes-at-hand/"><u>Mastery Over Malfunctioning Windows: Easy Fixes at Hand!</u></a></li>
<li><a href="https://windows11.techidaily.com/instant-change-of-windows-dashboard-background/"><u>Instant Change of Windows Dashboard Background</u></a></li>
<li><a href="https://windows11.techidaily.com/smoothing-out-chrome-profile-hitches-on-windows-systems/"><u>Smoothing Out Chrome Profile Hitches on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/tackle-non-selectable-text-in-windows-based-pdf-documents-easily/"><u>Tackle Non-Selectable Text in Windows-Based PDF Documents Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/the-elusive-guide-to-unseen-menu-adjustments-windows-style/"><u>The Elusive Guide to Unseen Menu Adjustments, Windows Style</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-asana-not-working-on-windows/"><u>How to Fix Asana Not Working on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/disregard-met-not-fulfilled-emblem-on-win11/"><u>Disregard Met Not Fulfilled Emblem on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/rejuvenating-your-apathetic-windows-start-button-click/"><u>Rejuvenating Your Apathetic Windows Start Button Click</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-causes-of-pc-disk-issues/"><u>Addressing Causes of PC Disk Issues</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-pinnacle-av-artisans-an-exclusive-list-for-you/"><u>[New] Pinnacle AV Artisans  An Exclusive List for You</u></a></li>
<li><a href="https://extra-hints.techidaily.com/beginners-bliss-how-to-set-up-and-manage-a-podcast-live-stream-easily/"><u>Beginner's Bliss  How to Set Up and Manage a Podcast Live Stream Easily</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/odins-last-hope-the-ragnarok-revelation/"><u>Odin's Last Hope  The Ragnarok Revelation</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-9-essential-iphone-x-hacks-for-every-user/"><u>[New] 9 Essential iPhone X Hacks for Every User</u></a></li>
<li><a href="https://extra-resources.techidaily.com/capture-safeguard-and-soar-top-cloud-options-reviewed-for-2024/"><u>Capture, Safeguard, and Soar - Top Cloud Options Reviewed for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/enhancing-audio-visual-experience-with-youtube-music-insertion/"><u>Enhancing Audio-Visual Experience with YouTube Music Insertion</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/getting-started-with-google-meet-participation/"><u>Getting Started with Google Meet Participation</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-edit-like-a-pro-top-40-keyboard-shortcuts-for-final-cut-pro-x/"><u>New In 2024, Edit Like a Pro Top 40 Keyboard Shortcuts for Final Cut Pro X</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/theme-that-stands-out-crafting-banners-for-gamers/"><u>Theme That Stands Out  Crafting Banners for Gamers</u></a></li>
<li><a href="https://techidaily.com/vivo-data-retrieval-tool-restore-lost-data-from-vivo-t2x-5g-by-fonelab-android-recover-data/"><u>Vivo Data Retrieval tool – restore lost data from Vivo T2x 5G</u></a></li>
</ul></div>
