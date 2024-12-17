---
title: Overcoming Stubbornness in Windows UI Elements
date: 2024-12-09T22:02:42.561Z
updated: 2024-12-16T20:16:42.137Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Stubbornness in Windows UI Elements
excerpt: This Article Describes Overcoming Stubbornness in Windows UI Elements
keywords: Windows Stubborn UI,UI Overcoming Tips,User Interface Challenges,Resilient UI Strategies,UI Element Adaptability,Ease Windows UI,UI Persistence Fixing
thumbnail: https://thmb.techidaily.com/c47546ef14b433a853f147293a1e027910647d2b3c636b3d7439e396fc35c411.jpg
---

## Overcoming Stubbornness in Windows UI Elements

 Task Manager is one of the most important Windows 11/10 system utilities. So, it’s a big issue when Task Manager is not working. Some users have reported Task Manager not opening (working) for them when they try to access it.

 Task Manager might throw up an error message or simply not respond when it’s not working. Task Manager opens with a blank window and crashes soon after for some users. Users can’t utilize Task Manager when it’s not working. This is how you can fix Task Manager not working on a Windows 11/10 PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZeYbTVeaXg0?si=rwLL1DbBoX26BGjm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Run System File and Image Repair Commands

 Many users have confirmed running system file and image repair commands can fix the Task Manager not working. So, that’s one of the first things you should try for fixing Task Manager when it’s not opening.

 To apply this potential solution, you’ll need to input separate Command Prompt commands for running the DISM (Deployment Image Servicing and Management) and SFC (System File Checker) tools. The SFC tool repairs system files and DISM services the Windows image.

 Follow the instructions in our article about [repairing corrupted Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) to run the SFC and DISM command-line tools.

![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/sfc-scannow-command2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S3Th6oa_isA?si=TTQ013BB9beUM4x6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Disable the Remove Task Manager Policy

 Group Policy Editor includes an option for disabling Task Manager. If you see an error message that states Task Manager is disabled, that option is likely enabled. Even if you don’t see an error message, you should still check the **Remove Task Manager** policy if you can access Group Policy Editor on your PC. This is how you can disable the **Remove Task Manager** policy:

1. [Open Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) on your Windows PC. If you're on Windows Home, you'll need to learn [how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) first.
2. Double-click **User Configuration** \> **Administrative Templates** \> **System** \> **Ctrl + Alt + Del Options** in Group Policy Editor’s sidebar.  
![The Ctrl+Alt+Del Options policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/remove-task-manager-policy.jpg)
3. Next, double-click **Remove Task Manager** to view a window for configuring that policy.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OFDHJnZLwTA?si=WThcb2h76AnZDzcQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Select **Disabled** or **Not Configured** if you find this policy enabled.  
![The Remove Task Manager window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/remove-task-manager-window.jpg)
5. Click **Apply** to set the new option for enabling Task Manager.

6. Then close the Remove Task Manager window by clicking **OK**.

 If this policy is not enabled, try turning it on and off. Click **Enabled** and **Apply** to activate the policy. Then select **Disabled**/**Not configured** to disable it.

## 3\. Initiate an Antivirus Scan

 Malware can sometimes be the reason for the Task Manager not working. Task Manager is targeted by malware because it’s an important system utility. So, [run an antivirus scan](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) with Windows Security or third-party security software to check for and purge malware from your PC. Select the most thorough antivirus scanning option in whatever option you utilize.

![The antivirus scan options in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/scan-now-option.jpg)

## 4\. Edit the Policies Key

 Note that running an antivirus scan might only eliminate the cause of this issue. Then you would still need to re-enable Task Manager to get it working after purging malware that disabled it. A virus will have likely disabled Task Manager in the registry. You can re-enable the Task Manager by editing the Policies registry key like this:

1. To access Registry Editor, press the **Windows key + S** key combination, enter a **regedit** keyword, and click the matching result shown in the search tool.
2. Next, go to the **Policies** key by inputting this path inside the registry address bar:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies`
3. Skip to step seven if you can see a **System** subkey. If you can’t, right-click **Policies** and select **New** \> **Key**.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-key-options.jpg)
4. Enter **System** in the new key’s text box.

5. Right-click **System** and select **New** \> **DWORD**.

1. Input **DisableTaskMgr** inside the DWORD’s text box.
2. Double-click the **DisableTaskMgr** DWORD within the **System** key.  
![The DisableTaskMgr DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disabletskmgr-dword.jpg)
3. The value for the **DisableTaskMrg** DWORD should be **0**. If it’s set any differently, erase the number in the **Value** box and input **0**.

4. Click **OK** to set the **DisableTaskMgr** value.  
![The Edit DWORD (32-bit) Value window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-edit-dword-window.jpg)
5. Now close the Registry Editor. To ensure the changes take effect, [restart your Windows PC](https://www.makeuseof.com/windows-restart-methods/) after editing the registry.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YezPJZzPJ8Q?si=xF1t4BQHFquzvnzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Run the PowerShell Command for Re-Registering Apps

 Some users say they managed to fix Task Manager by running a PowerShell command for reinstalling and registering built-in Windows 11/10 apps. If that worked for them, maybe this resolution will fix Task Manager not working on your PC. This is how you can run that PowerShell command:

1. Activate the **Type here to search** box by utilizing the **Windows key + S** keyboard shortcut.
2. Enter **PowerShell** inside the file search box.
3. Click **Run as administrator** for the matching PowerShell app search result.
4. Input this command:  
`Get-AppXPackage | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The PowerShell command that can fix Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-reinstall-apps-command.jpg)
5. Press **Enter** to execute the command and wait for it to finish before exiting PowerShell.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1dR4tF3VgyU?si=AJipgqZsNNxsRsBW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Change Your User Account

 Windows user account issues can also cause Task Manager to stop working. For example, your user account might be corrupted in some way. In this case, you can try to repair the corrupted user account or set up an entirely new one. Task Manager might work fine in a new user account.

 First, set up a new user account and sign into it to see if Task Manager works there. If it does, transfer all the user files from your old Windows account to the new one. Our guide to [fixing Windows issues by creating new accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) includes instructions for applying this troubleshooting method.

![The Add account button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/add-account-button.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/58KlTPHv8dU?si=7ICagyNgrao7OkVO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 7\. Restore Windows to an Earlier Time

 The System Restore tool can address some of the potential causes for Task Manager not working if you have it enabled. Much depends on whether you can select a restoration point that will roll Windows back to a date when Task Manager worked okay. If you can, rolling Windows back to an earlier time is worth a try when other potential solutions are ineffective.

 Our article about [how to utilize System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) tells you how to apply this potential fix. Choose a restoration point that will restore Windows to a time when you could utilize Task Manager without issues. You’ll need to reinstall desktop software and apps installed after a chosen restore point.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/system-restore-window.jpg)

## 8\. Reset Your Window PC

 This final resolution for the Task Manager not working is the most nuclear of the lot. Resetting Windows 11/10 will restore the platform to factory default settings by reinstalling it, which will obliterate malware and repair system file issues. It’s recommended as a last resort since resetting Windows will wipe out all the software you’ve installed.

 You can apply this potential resolution with the Reset this PC tool, as covered in this article about [resetting Windows 10 or 11](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/#:~:text=To%20access%20this%20Windows%20reinstall,this%20PC%20to%20get%20started.). There’s no need to back up user files since you can select a **Keep my files** option within the Reset this PC window. Make sure the **Reinstall preinstalled apps** option is selected to retain the software bundled with your PC.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/reset-this-pc-tool.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15Ju8Cb4UZ8?si=5wdiQXdz1BOxIkDH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Use Task Manager Within Windows Again

 Task Manager is not something most users can do without. Fortunately, the potential resolutions in this guide will likely resolve many of the Task Manager issues that prevent users from opening and utilizing that utility. At least one will probably kick-start Task Manager on your PC, enabling you to use that tool as required again.

 Task Manager might throw up an error message or simply not respond when it’s not working. Task Manager opens with a blank window and crashes soon after for some users. Users can’t utilize Task Manager when it’s not working. This is how you can fix Task Manager not working on a Windows 11/10 PC.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-cinematic-capture-a-device-friendly-movie-guidebook/"><u>[New] In 2024, Cinematic Capture A Device-Friendly Movie Guidebook</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-pivoting-from-srt-to-subtitle-format-for-2024/"><u>[New] Pivoting From SRT to Subtitle Format for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-taking-on-screen-capture-giants-how-bandicam-stacks-up-against-camtasia-for-2024/"><u>[Updated] Taking on Screen Capture Giants How Bandicam Stacks Up Against Camtasia for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/bridge-the-mc-lan-chasm-7-key-fixes-for-windows-users/"><u>Bridge the MC LAN Chasm: 7 Key Fixes for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/christmas-tech-surprises-through-microsofts-marketplace/"><u>Christmas Tech Surprises Through Microsoft's Marketplace</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-tutorial-for-extracting-dual-and-multi-archive-files/"><u>Comprehensive Tutorial for Extracting Dual and Multi-Archive Files</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-systemsettings-executable-errors-on-windows-11/"><u>Correcting SystemSettings Executable Errors on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/disabling-factory-seal-on-windows-11/"><u>Disabling Factory Seal on Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-airplane-mode-turn-off-gps-location-on-honor-90-gt-drfone-by-drfone-virtual-android/"><u>Does Airplane Mode Turn off GPS Location On Honor 90 GT? | Dr.fone</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/early-birds-guide-to-the-greatest-buy-out-prices-preceding-prime-day-2eek-june-2023/"><u>Early Bird's Guide to the Greatest Buy-Out Prices Preceding Prime Day 2Eek, June 2023</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-messages-files-from-huawei-p60-by-fonelab-android-recover-messages/"><u>How To Restore Missing Messages Files from Huawei P60</u></a></li>
<li><a href="https://win-answers.techidaily.com/ue4-challenges-conquered-deciphering-the-mystery-behind-arises-error-free-adventure/"><u>UE4 Challenges Conquered: Deciphering the Mystery Behind Arise's Error-Free Adventure</u></a></li>
</ul></div>

