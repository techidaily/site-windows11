---
title: Reinstating Functionality to Window Bar (Taskbar)
date: 2024-08-27T16:12:22.895Z
updated: 2024-08-28T16:12:22.895Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reinstating Functionality to Window Bar (Taskbar)
excerpt: This Article Describes Reinstating Functionality to Window Bar (Taskbar)
keywords: Windows Bar Fix,Taskbar Restore,Bar Function Reinstate,Bar Button Repair,Taskbar Enhancement,UI Window Issue,Icon Restoration Window
thumbnail: https://thmb.techidaily.com/0656fd665c6180b1a80265c93dba7068c3a0cbd851c23bc5b8909b9f9daa190b.jpg
---

## Reinstating Functionality to Window Bar (Taskbar)

 Task Manager is one of the most important Windows 11/10 system utilities. So, it’s a big issue when Task Manager is not working. Some users have reported Task Manager not opening (working) for them when they try to access it.

 Task Manager might throw up an error message or simply not respond when it’s not working. Task Manager opens with a blank window and crashes soon after for some users. Users can’t utilize Task Manager when it’s not working. This is how you can fix Task Manager not working on a Windows 11/10 PC.

## 1\. Run System File and Image Repair Commands

 Many users have confirmed running system file and image repair commands can fix the Task Manager not working. So, that’s one of the first things you should try for fixing Task Manager when it’s not opening.

 To apply this potential solution, you’ll need to input separate Command Prompt commands for running the DISM (Deployment Image Servicing and Management) and SFC (System File Checker) tools. The SFC tool repairs system files and DISM services the Windows image.

 Follow the instructions in our article about [repairing corrupted Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) to run the SFC and DISM command-line tools.

![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/sfc-scannow-command2.jpg)

## 2\. Disable the Remove Task Manager Policy

 Group Policy Editor includes an option for disabling Task Manager. If you see an error message that states Task Manager is disabled, that option is likely enabled. Even if you don’t see an error message, you should still check the **Remove Task Manager** policy if you can access Group Policy Editor on your PC. This is how you can disable the **Remove Task Manager** policy:

1. [Open Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) on your Windows PC. If you're on Windows Home, you'll need to learn [how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) first.
2. Double-click **User Configuration** \> **Administrative Templates** \> **System** \> **Ctrl + Alt + Del Options** in Group Policy Editor’s sidebar.  
![The Ctrl+Alt+Del Options policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/remove-task-manager-policy.jpg)
3. Next, double-click **Remove Task Manager** to view a window for configuring that policy.
4. Select **Disabled** or **Not Configured** if you find this policy enabled.  
![The Remove Task Manager window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/remove-task-manager-window.jpg)
5. Click **Apply** to set the new option for enabling Task Manager.
6. Then close the Remove Task Manager window by clicking **OK**.

 If this policy is not enabled, try turning it on and off. Click **Enabled** and **Apply** to activate the policy. Then select **Disabled**/**Not configured** to disable it.

## 3\. Initiate an Antivirus Scan

 Malware can sometimes be the reason for the Task Manager not working. Task Manager is targeted by malware because it’s an important system utility. So, [run an antivirus scan](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) with Windows Security or third-party security software to check for and purge malware from your PC. Select the most thorough antivirus scanning option in whatever option you utilize.

![The antivirus scan options in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/scan-now-option.jpg)

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Edit the Policies Key

 Note that running an antivirus scan might only eliminate the cause of this issue. Then you would still need to re-enable Task Manager to get it working after purging malware that disabled it. A virus will have likely disabled Task Manager in the registry. You can re-enable the Task Manager by editing the Policies registry key like this:

1. To access Registry Editor, press the **Windows key + S** key combination, enter a **regedit** keyword, and click the matching result shown in the search tool.
2. Next, go to the **Policies** key by inputting this path inside the registry address bar:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies`
3. Skip to step seven if you can see a **System** subkey. If you can’t, right-click **Policies** and select **New** \> **Key**.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-key-options.jpg)
4. Enter **System** in the new key’s text box.
<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Right-click **System** and select **New** \> **DWORD**.

1. Input **DisableTaskMgr** inside the DWORD’s text box.
2. Double-click the **DisableTaskMgr** DWORD within the **System** key.  
![The DisableTaskMgr DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disabletskmgr-dword.jpg)
3. The value for the **DisableTaskMrg** DWORD should be **0**. If it’s set any differently, erase the number in the **Value** box and input **0**.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Click **OK** to set the **DisableTaskMgr** value.  
![The Edit DWORD (32-bit) Value window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-edit-dword-window.jpg)
5. Now close the Registry Editor. To ensure the changes take effect, [restart your Windows PC](https://www.makeuseof.com/windows-restart-methods/) after editing the registry.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
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

## 6\. Change Your User Account

 Windows user account issues can also cause Task Manager to stop working. For example, your user account might be corrupted in some way. In this case, you can try to repair the corrupted user account or set up an entirely new one. Task Manager might work fine in a new user account.

 First, set up a new user account and sign into it to see if Task Manager works there. If it does, transfer all the user files from your old Windows account to the new one. Our guide to [fixing Windows issues by creating new accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) includes instructions for applying this troubleshooting method.

![The Add account button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/add-account-button.jpg)

## 7\. Restore Windows to an Earlier Time

 The System Restore tool can address some of the potential causes for Task Manager not working if you have it enabled. Much depends on whether you can select a restoration point that will roll Windows back to a date when Task Manager worked okay. If you can, rolling Windows back to an earlier time is worth a try when other potential solutions are ineffective.

 Our article about [how to utilize System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) tells you how to apply this potential fix. Choose a restoration point that will restore Windows to a time when you could utilize Task Manager without issues. You’ll need to reinstall desktop software and apps installed after a chosen restore point.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/system-restore-window.jpg)

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
## 8\. Reset Your Window PC

 This final resolution for the Task Manager not working is the most nuclear of the lot. Resetting Windows 11/10 will restore the platform to factory default settings by reinstalling it, which will obliterate malware and repair system file issues. It’s recommended as a last resort since resetting Windows will wipe out all the software you’ve installed.

 You can apply this potential resolution with the Reset this PC tool, as covered in this article about [resetting Windows 10 or 11](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/#:~:text=To%20access%20this%20Windows%20reinstall,this%20PC%20to%20get%20started.). There’s no need to back up user files since you can select a **Keep my files** option within the Reset this PC window. Make sure the **Reinstall preinstalled apps** option is selected to retain the software bundled with your PC.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/reset-this-pc-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
## Use Task Manager Within Windows Again

 Task Manager is not something most users can do without. Fortunately, the potential resolutions in this guide will likely resolve many of the Task Manager issues that prevent users from opening and utilizing that utility. At least one will probably kick-start Task Manager on your PC, enabling you to use that tool as required again.

 Task Manager might throw up an error message or simply not respond when it’s not working. Task Manager opens with a blank window and crashes soon after for some users. Users can’t utilize Task Manager when it’s not working. This is how you can fix Task Manager not working on a Windows 11/10 PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-tips.techidaily.com/updated-the-evolved-examination-of-sony-bdp-s3700/"><u>[Updated] The Evolved Examination of Sony BDP-S3700</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/2024-approved-breaking-into-the-tiktok-livestream-realm/"><u>2024 Approved  Breaking Into the TikTok Livestream Realm</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-bridging-moments-creating-fluid-edits-with-inshot/"><u>2024 Approved  Bridging Moments  Creating Fluid Edits with Inshot</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-move-contacts-from-realme-gt-5-pro-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Move Contacts From Realme GT 5 Pro to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://discover-advanced.techidaily.com/abbyy-anleitung-zur-elektronischen-rechnungsstellungsmethode-im-kontext-von-rechnungsabrechnungen-ein-praktischer-leitfaden/"><u>ABBYY-Anleitung Zur Elektronischen Rechnungsstellungsmethode Im Kontext Von Rechnungsabrechnungen: Ein Praktischer Leitfaden</u></a></li>
<li><a href="https://location-social.techidaily.com/change-location-on-yik-yak-for-your-poco-c50-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>Change Location on Yik Yak For your Poco C50 to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/guiding-you-through-ea-server-connection-troubles/"><u>Guiding You Through EA Server Connection Troubles</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-activate-and-use-life360-ghost-mode-on-nubia-red-magic-8s-pro-drfone-by-drfone-virtual-android/"><u>How To Activate and Use Life360 Ghost Mode On Nubia Red Magic 8S Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-break-free-from-frozen-dark-ui-settings/"><u>How to Break Free From Frozen Dark UI Settings</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-improve-network-stability-in-windows-11-systems/"><u>How to Improve Network Stability in Windows 11 Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-quickly-resolve-windows-11-error-0x800f0922/"><u>How To Quickly Resolve Windows 11 Error 0X800F0922</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-hypervisor-bsos-a-windows-expert-guide/"><u>How to Rectify Hypervisor BSOS: A Windows Expert Guide</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-sim-unlock-realme-gt-neo-5-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>In 2024, Sim Unlock Realme GT Neo 5 Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/keeping-apps-fixed-in-task-manager-on-pc/"><u>Keeping Apps Fixed in Task Manager on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/legacys-latest-look-instructions-for-windows-11-using-to-go-and-rufus-technology/"><u>Legacy's Latest Look: Instructions for Windows 11, Using To Go & Rufus Technology</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-the-installation-of-windows-11-arm-from-iso/"><u>Mastering the Installation of Windows 11 ARM From ISO</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-and-native-accounts-key-differences-unpacked-in-os-windows/"><u>Microsoft & Native Accounts: Key Differences Unpacked in OS Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-git-workflows-using-github-desktop-in-windows-11/"><u>Navigating Git Workflows Using GitHub Desktop in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11-a-detailed-guide-to-its-auto-hdr-function/"><u>Navigating Windows 11: A Detailed Guide to Its Auto HDR Function</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-patches-in-an-offline-world/"><u>Navigating Windows Patches in an Offline World</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-operation-failure-x709/"><u>Overcoming Windows Operation Failure X709</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-self-lock-in-windows-os/"><u>Preventing Self-Lock in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/privacy-control-remove-your-email-in-login-screen/"><u>Privacy Control: Remove Your Email in Login Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-uninstall-guide-windows-11s-best-practices-102-chars/"><u>Quick Uninstall Guide: Windows 11'S Best Practices (102 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-disconnected-messages-in-windows-discord/"><u>Rectifying Disconnected Messages in Windows Discord</u></a></li>
<li><a href="https://windows11.techidaily.com/resolve-your-black-screen-woes-with-simple-tricks-for-win11/"><u>Resolve Your Black Screen Woes with Simple Tricks for Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/restarting-progress-solving-qbittorrent-pauses-on-windows/"><u>Restarting Progress: Solving qBittorrent Pauses on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/reversing-roblox-errors-on-microsoft-os/"><u>Reversing Roblox Errors on Microsoft OS</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-code-0xc0000142-on-windows-xp-1011/"><u>Solving Code 0XC0000142 on Windows XP, 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/super-fast-windows-query-with-everythingapp/"><u>Super-Fast Windows Query with EverythingApp</u></a></li>
<li><a href="https://windows11.techidaily.com/tech-tricks-blend-taskbar-language-feature-win11-style/"><u>Tech Tricks: Blend Taskbar Language Feature, Win11 Style</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/ultimate-battle-royale-pros-and-cons-for-racing-drones-from-tb09-to-f5x-and-beyond/"><u>Ultimate Battle Royale: Pros & Cons for Racing Drones - From TB09 to F5X and Beyond</u></a></li>
<li><a href="https://windows11.techidaily.com/unfolding-windows-solutions-for-stubborn-folders-on-double-click/"><u>Unfolding Windows: Solutions for Stubborn Folders on Double-Click</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-sync-issues-with-7-innovative-windows-techniques/"><u>Unlocking Sync Issues with 7 Innovative Windows Techniques</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/updated-2024-approved-how-to-start-a-private-live-stream-on-youtube/"><u>Updated 2024 Approved How To Start a Private Live Stream on YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/what-to-do-if-the-mail-and-calendar-app-wont-open-in-windows-11/"><u>What to Do if the Mail and Calendar App Won’t Open in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11-productivity-push-crafting-uwp-shortcuts/"><u>Windows 11 Productivity Push: Crafting UWP Shortcuts</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>