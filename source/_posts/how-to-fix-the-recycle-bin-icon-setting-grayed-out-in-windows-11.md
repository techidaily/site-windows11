---
title: How to Fix the Recycle Bin Icon Setting Grayed Out in Windows 11
date: 2024-08-31T22:14:48.560Z
updated: 2024-09-01T22:14:48.560Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the Recycle Bin Icon Setting Grayed Out in Windows 11
excerpt: This Article Describes How to Fix the Recycle Bin Icon Setting Grayed Out in Windows 11
keywords: Win11 Recycle Graying,Fix Recycle Icon,Recycle Icon Issue,Set Icon Windows,Revive Bin Icon,Grayed Out Icon,Restore Recycling Bin
thumbnail: https://thmb.techidaily.com/ad4388017aad038e4020bb83bed704ce1407b9c4acd2fda68cb5e54d580ca0be.jpg
---

## How to Fix the Recycle Bin Icon Setting Grayed Out in Windows 11

 The Recycle Bin has been a staple on Windows for a long time, but not everyone wants it on the desktop. You can disable it via the Desktop Icon Settings, but there is a bug where if you try to re-enable it, the "Recycle Bin" option is grayed out and cannot be toggled.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

## 1\. How to Bring Back the Recycle Bin Using the Group Policy Editor

 The Group Policy Editor lets you show or hide the Recycle Bin icon from the desktop. Check if you have modified and accidentally disabled the Recycle Bin group policy recently. If so you can set the Remove Recycle Bin icon from the desktop policy to "Not Configured" which will restore it.

 You may not find the Local Group Policy Editor in Windows Home Edition. However, you can run a batch script to [enable Group Policy Editor on the Windows Home edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) or skip to the Registry Editor-based fix in the next step.

 To restore the Recycle Bin icon using the Group Policy Editor:

1. Press **Win + R** to open **Run**.
2. Type **gpedit.msc** and click **OK** to open the **Group Policy Editor**.  
![gpedit msc windows 11 run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/gpedit-msc-windows-11-run.jpg)
3. Next, navigate to the following location:  
`User Configuration > Administrative Templates > Desktop`
4. In the right pane, locate and double-click on the **Remove Recycle Bin icon from the desktop** option to open its properties.  
![edit remove recycle bin icon from settings gpedit policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-remove-recycle-bin-icon-from-settings-gpedit-policy.jpg)
5. In the **Properties** dialog, select **Not Configured**.  
![edit remove recycle bin icon from settings gpedit policy not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-remove-recycle-bin-icon-from-settings-gpedit-policy-not-configured.jpg)
6. Click **Apply** and **OK** to save the changes.

 Close the Group Policy Editor and check your desktop to see if you can access the Recycle Bin. If not, make sure the Recycle Bin is set to show in Desktop Icon Settings.

 To enable Recycle Bin in Desktop Icon Settings:

1. Press **Win + I** to open **Settings**.
2. Next, open the **Personalization** tab in the left panel.
3. Click on **Themes**.  
![desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/desktop-icon-settings-windows-11.jpg)
4. Click on **Desktop icon settings** under the **Related settings** section.
5. In the **Desktop Icon Settings** dialog, select **Recycle Bin**.  
![enable recycle bin desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/enable-recycle-bin-desktop-icon-settings-windows-11.jpg)
6. Click **Apply** and **OK** to save the changes.

 If you can’t access Group Policy Editor or if the issue persists, you can use the Registry Editor to fix this problem.

## 2\. Modify the Recycle Bin Registry Settings

 Another way to resolve and restore the grayed-out Recycle Bin icon in the Desktop settings is via the Windows Registry. You can modify the registry entry value responsible for the settings and configurations of Recycle Bin working to restore the functionality.

 Making modifications to the Windows registry involves tweaking settings that may harm your device if performed incorrectly. We recommend you [create a Windows restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [take a Windows registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before attempting to modify the Windows registry.

 To modify the Recycle Bin registry value:

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK**. Click **Yes** if prompted by **User Account Control**.
3. In the Registry Editor, navigate to the following location. You can copy and paste the path in the editor for quicker navigation:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\NonEnum`
4. In the right pane, locate the **{645FF040-5081-101B-9F08-00AA002F954E}** DWORD (32-bit) value.  
![registry editor nonnum new dword value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value.jpg)
5. If it does not exist, you’ll need to create a new value. To do this, right-click on the **NonEnum** subkey folder in the left pane and select **New > DWORD (32-bit) Value**.
6. Rename the value as **{645FF040-5081-101B-9F08-00AA002F954E}**.
7. Next, double-click on the new DWORD value to open its properties.  
![registry editor nonnum new dword value edit 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value-edit-0.jpg)
8. Type **0** in the Value data field and click **OK** to save the changes.
9. Close Registry Editor and restart your computer. Sometimes, you’ll need to restart your computer for the new registry modifications to work.

 If the issue persists, try to [create a new user account with administrative rights](https://www.makeuseof.com/windows-11-create-local-user-account/), [perform a system restore](https://www.makeuseof.com/use-system-restore-windows/), or [repair corrupted Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get Access to the Recycle Bin Desktop Icon Setting Again

 An incorrectly modified group policy can gray out the Recycle Bin icon in the Desktop Icon Settings dialog. Fortunately, it's an easy fix, and you should now have your Recycle Bin back to how you like it.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-subtitle-strategies-for-multilingual-instagram-videos/"><u>[New] 2024 Approved  Subtitle Strategies for Multilingual Instagram Videos</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-crafting-link-driven-success-a-backlink-blueprint-for-channels/"><u>[New] In 2024, Crafting Link-Driven Success  A Backlink Blueprint for Channels</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-integrating-harmonious-sounds-into-your-canva-videos/"><u>[New] Integrating Harmonious Sounds Into Your Canva Videos</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-ranked-your-must-have-5-iphones-for-excellent-podcasting-for-2024/"><u>[New] Ranked  Your Must-Have 5 iPhones for Excellent Podcasting for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/change-location-on-yik-yak-for-your-realme-10t-5g-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>Change Location on Yik Yak For your Realme 10T 5G to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/elevate-your-digital-footprint-crafting-compelling-shorts-thumbnails-for-2024/"><u>Elevate Your Digital Footprint  Crafting Compelling Shorts Thumbnails for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-microsoft-works-on-windows-latest-editions/"><u>Essential Guide to Microsoft Works on Windows Latest Editions</u></a></li>
<li><a href="https://windows11.techidaily.com/financial-success-in-w11-microsofts-blueprint/"><u>Financial Success in W11: Microsoft's Blueprint</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-avoid-auto-snip-from-prtscreen-keypress-in-11-windows/"><u>How to Avoid Auto-Snip From PrtScreen Keypress in 11 Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-execute-the-windows-startup-check/"><u>How to Execute the Windows Startup Check</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-jump-start-your-pc-beyond-s-mode-limits/"><u>How to Jump-Start Your PC Beyond S Mode Limits</u></a></li>
<li><a href="https://windows11.techidaily.com/identifying-and-correcting-uninstalled-hdd-errors-on-windows-11-pc/"><u>Identifying & Correcting Uninstalled HDD Errors on Windows 11 PC</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-infinix-hot-40-pro-drfone-by-drfone-virtual/"><u>In 2024, 9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Infinix Hot 40 Pro | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-from-infinix-zero-30-5g-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock from Infinix Zero 30 5G Phones with/without a PC</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-successfully-bypass-icloud-activation-lock-on-apple-iphone-15-pro-by-drfone-ios/"><u>In 2024, How to Successfully Bypass iCloud Activation Lock on Apple iPhone 15 Pro</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-learn-how-everything-works-on-honor-play-40c-drfone-by-drfone-virtual-android/"><u>Life360 Learn How Everything Works On Honor Play 40C | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-empty-folder-location-and-deletion-in-windows/"><u>Mastering Empty Folder Location and Deletion in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-wi-fi-settings-seamless-action-integration-on-microsoft-devices/"><u>Mastering Wi-Fi Settings: Seamless Action Integration on Microsoft Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-wpm-in-windows-11-a-step-by-step-guide/"><u>Mastering WPM in Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-common-obs-error-fixes-on-windows-11/"><u>Mastery of Common OBS Error Fixes on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11-netstat-to-monitor-tcpip-activity/"><u>Navigating Windows 11 Netstat to Monitor TCP/IP Activity</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-win11s-installer-lacks-permissions-issue/"><u>Overcoming Win11's Installer Lacks Permissions Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/proactive-battery-status-enabling-full-charge-alerts-in-windows-11/"><u>Proactive Battery Status: Enabling Full Charge Alerts in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fixes-for-onedrive-x-error-code-sign-in-woes-on-windows-11/"><u>Quick Fixes for OneDrive X-Error Code: Sign In Woes on Windows 11</u></a></li>
<li><a href="https://win-forum.techidaily.com/quick-guide-to-clean-up-your-pc-delete-with-command-line-in-windows-11/"><u>Quick Guide to Clean Up Your PC: Delete with Command Line in Windows 11</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/record-and-relive-iphoneandroid-google-meet-sessions-for-2024/"><u>Record and Relive  IPhone/Android Google Meet Sessions for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-operational-issues-with-windows-tablet-stylus/"><u>Rectifying Operational Issues with Windows Tablet Stylus</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-external-monitor-connectivity-problems-in-windows/"><u>Resolving External Monitor Connectivity Problems in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-lost-contacts-steam-fixes-for-windows-11/"><u>Restoring Lost Contacts: Steam Fixes for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-normalcy-notepad-on-windows-recovery/"><u>Restoring Normalcy: Notepad on Windows Recovery</u></a></li>
<li><a href="https://windows11.techidaily.com/revolutionizing-workflow-management-microsofts-ai-companion-on-windows-11-taskbar/"><u>Revolutionizing Workflow Management: Microsoft's AI Companion on Windows 11 Taskbar</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-your-system-with-these-7-budget-friendly-password-tools/"><u>Secure Your System with These 7 Budget-Friendly Password Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/sidestep-denied-login-issues-in-windows-with-easy-fixes/"><u>Sidestep Denied Login Issues in Windows with Easy Fixes</u></a></li>
<li><a href="https://android-transfer.techidaily.com/solved-move-from-poco-x6-pro-to-ios-not-working-problems-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Solved Move from Poco X6 Pro to iOS not Working Problems | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-method-to-activate-dark-mode-in-notepad-on-windows-11-pcs/"><u>Stepwise Method to Activate Dark Mode in Notepad on Windows 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/strengthening-windows-11-enhanced-mobile-accessibility/"><u>Strengthening Windows 11: Enhanced Mobile Accessibility</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-in-use-status-on-network-resources-in-windows-11/"><u>Tackling 'In-Use' Status on Network Resources in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-usb-non-attachment-problems-in-virtualbox-on-your-pc/"><u>Tackling USB Non-Attachment Problems in VirtualBox on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-disabling-onedrive-on-windows-11s-explore/"><u>Tips for Disabling OneDrive on Windows 11'S Explore</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-remedying-windows-11-logins/"><u>Understanding & Remedying Windows 11 Logins</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-full-task-mastery-administrative-run-in-task-manager-on-win11/"><u>Unlocking Full Task Mastery: Administrative Run in Task Manager on Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/what-hides-in-ftdibussys-windows-memory-integrity-disruption/"><u>What Hides in ftdibus.sys: Windows' Memory Integrity Disruption</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-guide-nullify-local-account-security-prompts/"><u>Win 11 Guide: Nullify Local Account Security Prompts</u></a></li>
<li><a href="https://windows11.techidaily.com/win-11-tips-disabling-unwanted-mouse-speed-boosting/"><u>Win 11 Tips: Disabling Unwanted Mouse Speed Boosting</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-and-10-home-enabling-administrator-access/"><u>Win11 & 10 Home: Enabling Administrator Access</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-ready-effective-microsoft-works-installation/"><u>Win11 Ready: Effective Microsoft Works Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-powered-disk-cloning-no-add-ons-needed/"><u>Windows-Powered Disk Cloning, No Add-Ons Needed</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>