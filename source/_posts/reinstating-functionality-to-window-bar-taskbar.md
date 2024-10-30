---
title: Reinstating Functionality to Window Bar (Taskbar)
date: 2024-10-23T16:54:19.286Z
updated: 2024-10-30T16:22:40.416Z
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

<!-- affiliate ads begin -->
<a href="https://oneplusfr.sjv.io/c/5597632/1622438/14044" target="_top" id="1622438">
  <img src="//a.impactradius-go.com/display-ad/14044-1622438" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://oneplusfr.sjv.io/i/5597632/1622438/14044" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Disable the Remove Task Manager Policy

 Group Policy Editor includes an option for disabling Task Manager. If you see an error message that states Task Manager is disabled, that option is likely enabled. Even if you don’t see an error message, you should still check the **Remove Task Manager** policy if you can access Group Policy Editor on your PC. This is how you can disable the **Remove Task Manager** policy:

1. [Open Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) on your Windows PC. If you're on Windows Home, you'll need to learn [how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) first.
2. Double-click **User Configuration** \> **Administrative Templates** \> **System** \> **Ctrl + Alt + Del Options** in Group Policy Editor’s sidebar.  
![The Ctrl+Alt+Del Options policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/remove-task-manager-policy.jpg)
3. Next, double-click **Remove Task Manager** to view a window for configuring that policy.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135356/19272" target="_top" id="2135356">
  <img src="//a.impactradius-go.com/display-ad/19272-2135356" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135356/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://laganoo.pxf.io/c/5597632/1528681/16446" target="_top" id="1528681">
  <img src="//a.impactradius-go.com/display-ad/16446-1528681" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528681/16446" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137203/26400" target="_top" id="2137203">
  <img src="//a.impactradius-go.com/display-ad/26400-2137203" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137203/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Restore Windows to an Earlier Time

 The System Restore tool can address some of the potential causes for Task Manager not working if you have it enabled. Much depends on whether you can select a restoration point that will roll Windows back to a date when Task Manager worked okay. If you can, rolling Windows back to an earlier time is worth a try when other potential solutions are ineffective.

 Our article about [how to utilize System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) tells you how to apply this potential fix. Choose a restoration point that will restore Windows to a time when you could utilize Task Manager without issues. You’ll need to reinstall desktop software and apps installed after a chosen restore point.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/system-restore-window.jpg)

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137976/21526" target="_top" id="2137976">
  <img src="//a.impactradius-go.com/display-ad/21526-2137976" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137976/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 8\. Reset Your Window PC

 This final resolution for the Task Manager not working is the most nuclear of the lot. Resetting Windows 11/10 will restore the platform to factory default settings by reinstalling it, which will obliterate malware and repair system file issues. It’s recommended as a last resort since resetting Windows will wipe out all the software you’ve installed.

 You can apply this potential resolution with the Reset this PC tool, as covered in this article about [resetting Windows 10 or 11](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/#:~:text=To%20access%20this%20Windows%20reinstall,this%20PC%20to%20get%20started.). There’s no need to back up user files since you can select a **Keep my files** option within the Reset this PC window. Make sure the **Reinstall preinstalled apps** option is selected to retain the software bundled with your PC.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/reset-this-pc-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135417/19272" target="_top" id="2135417">
  <img src="//a.impactradius-go.com/display-ad/19272-2135417" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135417/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-top-5-ios-applications-bringing-your-podcast-to-life/"><u>[New] 2024 Approved Top 5 iOS Applications Bringing Your Podcast to Life</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-how-to-record-audio-on-windows-11/"><u>[New] How To Record Audio on Windows 11?</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-in-2024-the-efficient-path-to-time-stamped-image-documentation/"><u>[New] In 2024, The Efficient Path to Time-Stamped Image Documentation</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/comparing-gopro-and-polaroids-video-editors-for-filmmakers-for-2024/"><u>Comparing GoPro & Polaroid's Video Editors for Filmmakers for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1723808323099-how-to-reduce-latency-for-gaming-2024-tips/"><u>How to Reduce Latency for Gaming – 2024 Tips</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-any-vivo-x90s-phone-password-using-emergency-call-by-drfone-android/"><u>How To Unlock Any Vivo X90S Phone Password Using Emergency Call</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-cortana-integration-vivetool-writings/"><u>Mastering Cortana Integration: ViveTool' Writings</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-access-to-system-status-and-update-information-via-menu-option-in-win11/"><u>Quick Access to System Status & Update Information via Menu Option in Win11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/quick-fixes-adding-descriptive-texts-to-videos-via-photos-app-windows-11-for-2024/"><u>Quick Fixes Adding Descriptive Texts to Videos via Photos App (Windows 11) for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/systematic-success-guiding-through-windows-11-renewal/"><u>Systematic Success: Guiding Through Windows 11 Renewal</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-arp-cache-explained-clears-and-management/"><u>Windows ARP Cache Explained: Clears & Management</u></a></li>
</ul></div>

